- BroadcastReceiver 是跨应用广播，利用Binder机制实现，支持动态和静态两种方式注册方式。
- LocalBroadcastReceiver 是应用内广播，利用Handler实现，利用了IntentFilter的match功能，提供消息的发布与接收功能，实现应用内通信，效率和安全性比较高，仅支持动态注册。

[BroadcastReceiver 与 LocalBroadcastReceiver 有什么区别？](https://github.com/Moosphan/Android-Daily-Interview/issues/11) 
