##启动Zookeeper和Warden

根据你在运行configure.sh 脚本时指定的选项，Zookeeper和Warden 或许已经被启动了。

检查Zookeeper是否已启动：
service mapr-zookeeper status

检查Warden是否已启动：
service mapr-warden status


## 启动Zookeeper和Warden，如果它们没有启动的话。 ##
1、在安装了它的节点上启动zookeeper，通过以下命令：
service mapr-zookeeper start

2、在所有节点上启动Warden.
service mapr-warden start

