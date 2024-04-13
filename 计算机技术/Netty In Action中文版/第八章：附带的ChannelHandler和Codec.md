1. **使用SSL/TLS创建安全的Netty程序**
   - 讨论了在网络上加密数据的重要性，并介绍了SSL和TLS协议。
   - 介绍了Netty中的`SslHandler`，它是`SslEngine`的包装类，用于对网络数据进行加密和解密。
   - 提供了使用`SslHandler`的示例代码，并讨论了SSL/TLS握手和关闭通知的超时设置。
2. **使用Netty创建HTTP/HTTPS程序**
   - 讨论了HTTP/HTTPS协议的用途和Netty提供的HTTP编解码器。
   - 介绍了`HttpRequestEncoder`、`HttpRequestDecoder`、`HttpResponseEncoder`和`HttpResponseDecoder`的使用方法。
   - 讨论了HTTP消息的聚合，以及如何使用`HttpObjectAggregator`处理HTTP消息。
3. **WebSocket**
   - 讨论了WebSocket协议的优势，包括实时数据传输和减少网络延迟。
   - 介绍了Netty中WebSocket的实现，包括`WebSocketServerProtocolHandler`和其他相关的`ChannelHandler`。
4. **SPDY**
   - 简要介绍了Google开发的SPDY协议，它是一种对HTTP协议的增强，用于减少网络延迟和优化用户体验。
5. **处理空闲连接和超时**
   - 讨论了网络应用程序中处理空闲连接和超时的重要性。
   - 介绍了`IdleStateHandler`、`ReadTimeoutHandler`和`WriteTimeoutHandler`的用途和配置方法。
6. **解码分隔符和基于长度的协议**
   - 讨论了Netty如何解码分隔符协议和基于长度的协议。
   - 介绍了`DelimiterBasedFrameDecoder`、`LineBasedFrameDecoder`、`FixedLengthFrameDecoder`和`LengthFieldBasedFrameDecoder`的使用方法。
7. **写大数据**
   - 讨论了在Netty中高效写入大量数据的方法，包括使用`DefaultFileRegion`和`ChunkedWriteHandler`。
8. **序列化数据**
   - 讨论了在网络程序中传输结构化对象数据的需求。
   - 介绍了Netty支持的序列化方法，包括JDK序列化、JBoss编组序列化和ProtoBuf序列化。
   - 提供了使用不同序列化方法的代码示例和配置方法。

本章为读者提供了Netty框架中附带的`ChannelHandler`和`Codec`的使用方法和实现细节，包括安全协议、HTTP/HTTPS、WebSocket、SPDY、处理空闲连接和超时、解码分隔符和基于长度的协议，以及写入大数据和序列化数据的技巧。通过这些知识，读者可以更好地利用Netty提供的丰富功能来构建高效、安全的网络应用程序。