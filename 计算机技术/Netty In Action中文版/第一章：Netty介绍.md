《Netty In Action中文版 - 第一章：Netty介绍》的大纲如下：

1. **为什么使用Netty**

   - 引用David John Wheeler的名言，讨论间接方法在解决计算机科学问题中的应用。

   - 强调Netty作为一个NIO client-server框架，提供了简化TCP和UDP服务器编程的高层次抽象。

     TODO  通过底层API 和通过NETTY 开发网络应用的经验

   - 讨论Netty的高性能、易用性、稳定性和扩展性，并提到一些使用Netty的知名公司和项目。

2. **Netty的功能非常丰富**

   - 描述Netty提供的各种功能，包括传输类型、线程模型、无连接的DatagramSocket支持等。
   - 讨论Netty在设计、易用性、性能、鲁棒性、安全性和社区方面的特色。

3. **异步设计**

   - 解释异步处理的重要性和如何提高资源利用效率。
   - 讨论异步API的两种实现方式：Callbacks（回调）和Futures，并比较它们的优缺点。

4. **Java中的Blocking和non-blocking IO对比**

   - 简要介绍Java的阻塞IO和非阻塞IO（NIO）的区别。

5. **NIO的问题和Netty中是如何解决这些问题的**

   - 讨论Java NIO的限制和设计问题。
   - 描述Netty如何解决跨平台和兼容性问题，扩展ByteBuffer，以及处理NIO的内存泄露问题。
   - 讨论epoll bug的问题和Netty的解决方案。

6. **Summary（总结）**

   - 总结本章内容，强调Netty的特点和如何解决NIO的问题。
   - 强调Netty为开发者提供了无需了解底层事件选择机制的简化API。
   - 提示读者在后续章节中将学习Netty API的基础知识，并使用Netty编写实用的网络代码。

本章为读者提供了Netty的概述，包括其设计理念、功能、异步处理机制以及如何解决Java NIO中的问题。通过本章的学习，读者可以对Netty有一个基本的了解，并为深入学习Netty打下坚实的基础。