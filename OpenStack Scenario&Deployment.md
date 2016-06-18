[]()[知识共享许可协议]()

opensourcecloud-specification 由 OSCAR 创作，采用知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议进行许可。

基于https://github.com/organizations/opensourcecloud/上的作品创作。

## OpenStack-Scenario

### 1 OpenStack应用场景概述

综述与趋势，问题与不足

### 2 OpenStack通用型应用场景

#### 1) 简单数据库场景

#### 2) Web应用场景

#### 3) 应用开发平台场景

#### 4) 测试实验平台

 

### 2 OpenStack计算型应用场景

#### 1) HPC高性能计算场景

#### 2) 分布式数据处理场景

#### 3) 持续集成CI与持续部署CD场景

#### 4) PaaS平台即服务场景

#### 5) 网络功能虚拟化NFV场景

 

### 3 OpenStack存储型应用场景

#### 1) 活跃归档、备份和分级存储管理场景

#### 2) 通用内容存储和同步场景

#### 3) 基于并行文件系统的数据分析场景

#### 4) 非结构化数据存储场景

#### 5) 持久化的块存储场景

#### 6) 操作系统和应用镜像存储场景

#### 7) 媒体流场景

#### 8) 数据库场景

#### 9) 云存储配对场景

 

### 4 OpenStack网络型应用场景

#### 1) 内容分发网络场景

#### 2) 网络管理功能场景

#### 3) 网络服务提供场景

#### 4) Web服务场景

#### 5) 高速及大量数据的事务系统场景

#### 6) 高可用场景

#### 7) 大数据网络场景

#### 8) 虚拟桌面基础设施(VDI) 场景

#### 9) IP 语音(VoIP) 场景

#### 10) 视频会议和 web 会议场景

 

### 5 OpenStack多区域应用场景

#### 1) 多分支/多站点场景

#### 2) 地理位置敏感场景

#### 3) 数据本地性场景

 

### 6 OpenStack混合云应用场景

#### 1) 私有云向公有云扩展场景

#### 2) 灾难恢复场景

#### 3) 开发和测试场景

#### 4) 联合云场景

#### 5) 传统系统的云迁移场景

 

### 7 OpenStack特殊应用场景

#### 1) 特殊网络应用场景

#### 2) 软件定义网络(SDN)应用场景

#### 3) 专用硬件应用场景

 

 

 

## OpenStack-Deploy

### 1 OpenStack的安装与部署概述

综述与趋势，流程与规范，问题与不足

 

### 2 OpenStack部署详述

#### 1) DevStack部署

DevStack提供了快速部署OpenStack云计算的工具、脚本和参数。

DevStack Github参考: [https://github.com/openstack-dev/devstack](https://github.com/openstack-dev/devstack)

 

#### 2) RDO部署

RDO是由RedHat开源的一款OpenStack部署工具。

RDO部署参考：[https://www.rdoproject.org/](https://www.rdoproject.org/)

 

#### 3) Ansible部署

Ansible提供源码部署OpenStack生产环境的方式

Ansible Github参考：[https://github.com/openstack/openstack-ansible](https://github.com/openstack/openstack-ansible)

 

 

#### 4) Fuel部署

Fuel是由Mirantis提供的图形化OpenStack部署工具。

Fuel部署参考：[https://www.mirantis.com/products/mirantis-openstack-software/](https://www.mirantis.com/products/mirantis-openstack-software/)

 

#### 5) Kolla部署

Kolla可通过Docker容器部署OpenStack服务。

Kolla部署参考：[http://docs.openstack.org/developer/kolla/quickstart.html](http://docs.openstack.org/developer/kolla/quickstart.html)

 

#### 6) 其他部署