html5  提供了在网页文档之间互相接收与发送消息的功能。
使用这个工能，只要获取到接收消息网页窗口对象的实例， 不仅同源的 web 网页之间可以互通，甚至可以实现跨域通信。 要想接收从其他窗口发送来的信息，必须对窗口对象的 onmessage(window.onmessage) 事件进行监听。
