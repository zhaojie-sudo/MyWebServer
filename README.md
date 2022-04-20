MyWebServer
====================
Linux下C++超轻量级Web服务器，用于学习实践Socket网络编程。

> * 使用 **线程池 + 非阻塞socket + epoll(ET和LT均实现) + 事件处理(模拟Proactor)** 的并发模型
> * 使用**状态机**解析HTTP请求报文，支持解析**GET**请求
> * 经Webbench压力测试可以实现**接近上万(9800)的并发连接**数据交换

运行
----------------
* build  
    `make`
* 启动server  
    `./server [port]`
* 浏览器  
    `ip:[port]/index.html`

参考资料
1. TCP/IP网络编程，[韩] 尹圣雨著.
2. Linux高性能服务器编程，游双著.
3. 牛客视频 https://www.nowcoder.com/study/live/504
4. b站视频教程 https://www.bilibili.com/video/BV1gg411P7hL?p=1