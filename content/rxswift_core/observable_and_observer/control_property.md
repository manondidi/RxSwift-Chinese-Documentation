## ControlProperty

**ControlProperty** 专门用于描述 **UI** 控件属性的，它具有以下特征：

* 不会产生 `error` 事件
* 一定在 `MainScheduler` 订阅（主线程订阅）
* 一定在 `MainScheduler` 监听（主线程监听）
* 共享状态变化
