# springcloud-config-server-demo
springcloud-config-server-demo：分布式配置中心demo（配置服务放在远程git仓库）
一．Eurekaserver：服务注册中心 测试地址：http://localhost:1111 
二．Springcloud-config-demo：配置中心config-server 测试地址：http://localhost:9003/config-client/dev/master
三．Configclient：客户端 测试地址：http://localhost:1112/ 
启动顺序依次是：服务注册中心-->配置中心-->客户端
配置文件远程git地址：https://github.com/yuki9467/config-repo
