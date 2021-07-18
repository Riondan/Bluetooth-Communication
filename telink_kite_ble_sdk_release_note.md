### Features
* SDK version：telink_kite_ble_sdk_V3.4.1.
* add long suspend function for sleep more than 1 hour
* add IR learn function.
* add Dmic config sample.
* optimize accesss code generation algorithm
* add "GAP_EVT_SMP_PARING_FAIL"callback for user
* optimize sample proj
* optimize secure connection
* modified MTU_SIZE buffer by user
* add ble 2M coded phy test feature
* optimze ota funtion
* add feature test for privacy test demo
* add extended_adv_connectable_undirected_demo
* Audio solution integration:
  +  Adpcm Telink Audio profile.
  +  Adpcm Google voice profile( Android O/P/Q ).
  +  Adpcm HID service ( RCU<->STB or RCU<->Telink Dongle ).
  +  Adpcm HID service ( RCU<->Telink Dongle<->STB ).
  +  SBC(8:1) HID service ( RCU<->STB or RCU<->Telink Dongle ).
  +  SBC(8:1) HID service ( RCU<->Telink Dongle<->STB ).
  +  mSBC(4.2:1) HID service ( RCU<->Telink Dongle ).

### Bug fix
* fix send event "GAP_EVT_MASK_SMP_PARING_BEGAIN" before "GAP_EVT_MASK_SMP_PARING_FAIL" 

### BREAKING CHANGES
  - N/A

### Features
* SDK版本：telink_kite_ble_sdk_V3.4.1.
* 添加长睡眠函数.
* 红外学习功能添加.
* Dmic 配置使用用例.
* 优化随机数生成算法.
* 为用户提供GAP_EVT_SMP_PARING_FAIL事件回调
* 优化了sample工程
* 开放MTU buffer缓存大小的定义.
* 提供 ble 2M coded phy 测试用例
* 优化了ota方案
* 增加privacy test 测试用例
* 增加了可连接非定向扩展广播包用例
* 语音解决方案集成:
  +  Adpcm Telink 语音方案.
  +  Adpcm Google 语音方案( Android O/P/Q ).
  +  Adpcm HID 通道语音方案 ( RCU<->STB or RCU<->Telink Dongle ).
  +  Adpcm HID 通道语音方案 ( RCU<->Telink Dongle<->STB ).
  +  SBC(8:1) HID 通道语音方案 ( RCU<->STB or RCU<->Telink Dongle ).
  +  SBC(8:1) HID 通道语音方案 ( RCU<->Telink Dongle<->STB ).
  +  mSBC(4.2:1) HID 通道语音方案 ( RCU<->Telink Dongle ).

###Bug fix
* 修复GAP_EVT_MASK_SMP_PARING_BEGAIN事件发送早于GAP_EVT_MASK_SMP_PARING_FAIL事件的问题

### BREAKING CHANGES
 -  N/A