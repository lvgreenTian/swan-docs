---
title: 模拟器 API 与真机的实现差异
header: develop
nav: devtools
sidebar: diff
---


API 在模拟器与真机中的实现差异如下：


|api |  差异| 
|---|---|
|[swan.getSystemInfo](https://smartprogram.baidu.com/docs/develop/api/device_sys/swan-getSystemInfo/) | 部分属性开发者工具暂不支持,详情请看详情页 |
|[swan.getSystemInfoSync](https://smartprogram.baidu.com/docs/develop/api/device_sys/swan-getSystemInfoSync/) | 部分属性开发者工具暂不支持,详情请看详情页 |
|[swan.compressImage](https://smartprogram.baidu.com/docs/develop/api/media_image/#swan-compressImage/) | 开发者工具暂不支持 | 
|[swan.getLocation](https://smartprogram.baidu.com/docs/develop/api/location/swan-getLocation/) | 工具暂不支持返回wgs84坐标系 | 
|[swan.onMemoryWarning](https://smartprogram.baidu.com/docs/develop/api/device_sys/onmemory/) | 通过“模拟操作->内存警告”触发 | 
|[swan.onNetworkStatusChange](https://smartprogram.baidu.com/docs/develop/api/device_sys/swan-onNetworkStatusChange/) | 通过“模拟操作->网络”切换网络触发 | 
|[swan.onCompassChange](https://smartprogram.baidu.com/docs/develop/api/device_sys/swan-onCompassChange/) | 返回模拟数据 | 
| [swan.onDeviceMotionChange](https://smartprogram.baidu.com/docs/develop/api/device_sys/swan-onDeviceMotionChange/)| 返回模拟数据, 通过“模拟操作->震动”触发| 
|[swan.scanCode](https://smartprogram.baidu.com/docs/develop/api/device_sys/swan-scanCode/) | 通过“模拟操作->扫码”设置扫码返回数据 | 
|[swan.onUserCaptureScreen](https://smartprogram.baidu.com/docs/develop/api/device_sys/swan-onUserCaptureScreen/) | 通过“模拟操作->截屏”触发 | 
|[swan.vibrateLong](https://smartprogram.baidu.com/docs/develop/api/device_sys/swan-vibrateLong/) | 开发者工具暂不支持 | 
| [swan.vibrateShort](https://smartprogram.baidu.com/docs/develop/api/device_sys/swan-vibrateShort/)| 开发者工具暂不支持 | 
| [swan.makePhoneCall](https://smartprogram.baidu.com/docs/develop/api/device_sys/swan-makePhoneCall/)| 弹窗提示接口调用成功 | 
|[swan.requestPolymerPayment](https://smartprogram.baidu.com/docs/develop/api/open/payment_swan-requestPolymerPayment/) | 工具暂不支持调起支付 | 
| [swan.chooseInvoiceTitle](https://smartprogram.baidu.com/docs/develop/api/open/swan-chooseInvoiceTitle/)| 提供模拟可选发票 | 
|[swan.navigateToSmartProgram](https://smartprogram.baidu.com/docs/develop/api/open/swan-navigateToSmartProgram/) | 开发者工具暂不支持 | 
|[swan.navigateBackSmartProgram](https://smartprogram.baidu.com/docs/develop/api/open/swan-navigateBackSmartProgram/) |  开发者工具暂不支持| 
|[swan.setEnableDebug](https://smartprogram.baidu.com/docs/develop/api/open/swan-setEnableDebug/)|开发者工具暂不支持|
|[swan.showFavoriteGuide](https://smartprogram.baidu.com/docs/develop/api/show/nacomponent/)| 为方便开发者开发和调试，该api在开发工具中并未使用引导组件的统一[策略](https://smartapp.baidu.com/docs/develop/api/show/nacomponent/)。|
|[swan.setInnerAudioOption](https://smartprogram.baidu.com/docs/develop/api/media/createinneraudiocontext_swan-setInnerAudioOption/)|开发者工具暂不支持| 
|[swan.ai.getVoiceRecognizer](https://smartprogram.baidu.com/docs/develop/api/ai_voice/#swan-ai-getVoiceRecognizer/)|开发者工具暂不支持| 
|[swan.shareFile](https://smartprogram.baidu.com/docs/develop/api/open_share/#swan-shareFile)|开发者工具暂不支持| 
