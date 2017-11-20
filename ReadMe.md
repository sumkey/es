## elasticsearch 说明文档

### 参数说明
```
初始化默认值
XMS 512m
XMX 512m
NETWORK_HOST 127.0.0.1
BOOTSTRAP_MEMORY_LOCK false
CLUSTER_NAME "my-application" 集群名称
NODE_NAME "node-1" 节点名称
NODE_MASTER true  是否主节点
NODE_DATA true  是否存储数据
NODE_ATTR_RACK "r1"
HTTP_POST 9200 设置对外服务的http端口,默认为9200 
DISCOVERY_ZEN_MINIMUM_MASTER_NODES 3
GATEWAY_RECOVER_AFTER_NODES 3
ACTION_DESTRUCTIVE_REQUIRES_NAME true
DISCOVERY_ZEN_PING_UNICAST_HOSTS '["127.0.0.1", "[::1]"]'
NETWORK_PUBLISH_HOST ""

```