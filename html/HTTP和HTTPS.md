HTTP协议通常承载于TCP协议之上，在HTTP和TCP之间添加一个安全协议层（SSL和TSL），这个时候，就成了我们常说的HTTPS。

默认HTTP的端口号是80.HTTPS的端口号是443

> 为什么HTTPS安全

因为网络请求需要中间有很多的服务器路由器的转发。中间的节点都可能篡改信息，而如果使用HTTPS，密钥在你和终点站才有。HTTPS之所以比http安全，是因为他利用ssl/tls协议传输。它包含证书，卸载，流量转发，负载均衡，页面适配，浏览器适配，refer传递等。保障了传输过程的安全性