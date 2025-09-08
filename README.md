# FFChat_StatusServer
# 分布式即时通讯项目
## 主要功能
 1. 用户登录时获取连接数最少的服务器ip和token

## 技术细节
    - 通过grpc与gateserver实现多服务器间通信
    - 封装mysql连接池，redis连接池，模板化grpc池
    - 高效的消息传递，事件处理机制
