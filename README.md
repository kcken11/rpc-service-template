# rpc-service-template #
zookeeper+redis+spring+mybatis+disconf

# 可启动版 遇到的坑 #

1. disconf-web ,zookeeper 同一台服务器 127.0.0.1:2181 访问不到 connect failed  后来改成域名：2181 成功   具体原因暂不明 有空再看看

2.  disconf-web 部署过程中  403 访问权限问题    ngnix.conf  #user root  被注释了  放开后解决  中间 也 chown -R 了好几次


