ZooKeeper 
动物园管理员
使用版本是3.4.13
下载路径https://archive.apache.org/dist/zookeeper/zookeeper-3.4.13/
cp zoo_sample.cfg zoo.cfg
需要修改里面data的存放路径，不要放在初始的tmp里面
对外访问的默认的端口是2181
常用命令是
./zkServer start
./zkServer status
./zkServer stop
./zkCli.sh -server ip:port,ip:port
