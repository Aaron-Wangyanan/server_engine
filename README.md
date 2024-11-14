# server_engine
基础的跨平台服务引擎，源码较为简单，没有提供makefile文件，高版本的ubuntu系统可能会报错

# 运行server
cd EasyTcpServer

g++ interactive_server.cpp -I header/ -o server

./server

# 运行client
cd EasyTcpClient

g++ client.cpp -I header/ -o client
