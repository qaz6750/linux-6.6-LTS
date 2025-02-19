# kernel_linux_common_6.6

## 介绍
* 本仓库主要是尝试在小米9上启动OpenHarmony，包含相关内核代码
* 仓用途：linux-6.6原生仓，包含linux-6.6原生代码。
* 其他内核通用说明详见：[内核文档](https://gitee.com/openharmony/docs/blob/master/zh-cn/device-dev/kernel/Readme-CN.md)
## 状态
### 系统
* OpenHarmony 启动未测试
* Linux 在UEFI的情况下启动良好
### 小米9
* WIFI
* 蓝牙
  * 很大概率无法启用
* 触摸
  * [BUG]FTS521驱动程序要求在启动的时候一直点击屏幕，进系统才有触摸可用  
* 电池
  * 可能存在部分数值错误
* Type—C
  * 目前无法随时切换模式
  * 充电速度非常慢    
* Gpu & 面板
  * GPU 工作目前看起来正常
  * 亮度调节: [BUG]当调节亮度时画面会出现撕裂，并且同时伴随日志:"dsi_err_worker: status=5"
* 声音
  * 完全不可用  
