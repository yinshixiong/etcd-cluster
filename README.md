# etcd-cluster
cfssl-etcd-cluster
-- #author: yinshixiong
#用于安装Etcd服务
#安装前需要将数组脚本内ip进行替换，如果多节点适当修改配置信息
-- 只需要修改globalClusterInfo.sh
        ---- server_arrays数组
          --etcd1 etcd2 etcd3 etcd4 etcd5 或者etcd1 etcd2 etcd3 或者 etcd1
