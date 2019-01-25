# Instruction

Linux, C++, Chat Room

https://simpledevcode.wordpress.com/2016/06/16/client-server-chat-in-c-using-sockets/

https://zhuanlan.zhihu.com/p/24475299

https://www.bogotobogo.com/cplusplus/sockets_server_client.php

Client-Server chat in C++

- Built a linux chat room based on client server model, communicating over TCP using sockets
- 1.客户端，客户端程序用poll同事坚挺用户输入和网络连接，并用splice 函数将用户输入直接定向到网络连接上发送，从而实现数据零拷贝。
- 2.服务器端，使用poll同事管理监听socket 和连接socket ，并且使用hash策略提升服务器性能



# MultiClientChatRoom

### Introducing Threads in Socket Programming in Java

https://www.geeksforgeeks.org/introducing-threads-socket-programming-java/



https://github.com/coderxj/select-model/tree/master/client

- built a multi client chat room based on client server model in C++, communicating over TCP using Sockets
- Handled multiple client requests at same time using Select
- Peer to peer
- 增加好友，删除好友，与好友私聊 Thread



# How to use select

https://gnomezgrave.com/2015/03/03/simple-client-server-chat-program-using-select/