## 操作场景
设备开发完成后，需要进入设备调试阶段调试设备与云端的通信是否正常。设备调试提供了真实设备在线调试及虚拟设备调试，并可通过控制台查询设备上报的当前数据、历史通信日志、事件及上下线记录等。本文档主要介绍如何进行设备调试。

LoRa 设备调试与其他产品的设备调试的操作步骤基本一致，只有新建设备时有不同，因此本文档中只对新建 LoRa 设备这一步骤进行说明，其他步骤可参考通用的 [设备调试](https://cloud.tencent.com/document/product/1081/34741) 文档。


## 前提条件
已完成设备开发。详情请参见 [LoRa 设备开发](https://cloud.tencent.com/document/product/1081/41189)。


## 操作步骤

1. 登录 [物联网开发平台控制台](https://console.cloud.tencent.com/iotexplorer)，设备开发完成后，单击【设备调试】。
2. 进入设备调试环节，单击【新建设备】，填写设备基本信息，单击【保存】，即可完成创建设备。
  - 设备名称：支持英文、数字、下划线的组合，最多不超过48个字符。
  - DevEUI：仅支持英文、数字，长度16位。
  - AppKey；仅支持英文、数字，长度32位。
 ![](https://main.qcloudimg.com/raw/7e977303f3bf6132cffc4272edd0460f.png)
3. 创建成功后，您将会在“设备调试”列表页中，查看到新建成功的设备。

