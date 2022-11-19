# icloud
Easily create cloud-servers by strong c++
C++服务器开发框架比较少，似乎需要花大量精力构建基础【比如网络通信，数据库访问，redis访问，业务服务协调管理等】，对于微服务系统更是比较难，本项目旨在给大家提供拿来即用的基础系统，可以快速开发自己的业务系统。

## service-server
+ manage business servers
+ servers online/offline
+ servers resource management

## auth-server
+ client identification
+ clients online/offline management
+ control center of business servers

## business-server


## features
+ poll/epoll tcp communication
+ database pool
+ client identification by SRP
+ message serialization by protobuf
+ cmake + conan build project

