Hetty
=====
Hetty是一款构建于netty和hessian基础上的高性能的RPC框架.hessian是一款基于HTTP协议的RPC框架，采用的是二进制RPC协议，非常轻量级
，且速度较快。netty是一款Netty基于事件驱动的NIO框架，用以快速开发高性能、高可靠性的网络服务器和客户端程序。Hetty客户端完全由
用hessian实现，只是使用netty对服务端进行了实现。