OpenStack是由NASA和Rackspace合作研发并发起的。

OpenStack是一个开源的云计算管理平台，由几个注意的组件组合起来完成具体的工作。OpenStack支持几乎所有类型的云环境，项目目标是提供实施简单，可大规模扩展、丰富、标准统一的云计算管理平台。OpenStack通过各种互补的服务提供了基础设施即服务（IaaS）的解决方案，每个服务提供API以进行集成。

OpenStack是一个旨在为公共及私有云的建设与管理提供软件的开源项目。OpenStack项目的首要任务是简化云的部署过程并为其带来良好的可扩展性。

####**运用范围**
OpenStack是IaaS（基础设施即服务）组件，让任何人都可以自行建立和提供云端运算服务。此外，OpenStack也用作建立防火墙的"私有云"，提供机构或企业内各部门共享资源。

####**项目**

**核心项目**
OpenStack覆盖了网络、虚拟化、操作系统、服务器等各个方面。是一个正在开发中的云计算平台项目，它包含了以下几个核心项目：

计算（Compute）：Nova。一套控制器，用于为单个用户或使用群组管理虚拟机实例的整个生命周期，根据用户需求来提供虚拟服务。负责虚拟机创建、开机、关机、挂起等操作，配置CPU、内存等信息规格。

对象存储（Object Storage）：Swift。一套用于大规模可扩展系统中通过内置冗余及高容错机制实现对象存储的系统，允许进行存储或者检索文件。

镜像服务（Image Service）：Glance。一套虚拟机镜像查找及检索系统，支持多种虚拟机镜像格式，有创建上传镜像、删除镜像、编辑镜像基本信息的功能。

身份服务（Identity Service）：Keystone。为OpenStack其他服务提供身份验证、服务规则和服务令牌的功能。

网络&地址管理（Network）：Neutron。提供云计算的网络虚拟化技术，为OpenStack其他服务提供网络连接服务。为用户提供接口，可以定义Network、Subnet、Router，配置DHCP、DNS、负载均衡、L3服务，网络支持GRE、VLAN。

块存储（Block Storeage）:Cinder。为运行实例提供稳定的数据块存储服务。

UI界面（Dashboard）：Horizon。OpenStack中各种服务的Web管理门户，用于简化用户对服务的操作。

测量（Metering）：Ceilometer。像一个漏斗一样，把OpenStack内部发生的所有事件都收集起来，然后计费和监控以及其他服务提供数据支撑。

部署编排（Orchestration）：Heat。提供一种通过模版定义的协同不熟方式，实现云基础设施软件运行环境的自动化部署。

数据库服务（Database Service）：Trove。为用户在OpenStack的环境提供可扩展和可靠的关系和非关系数据库引擎服务。

####**名词解释**

**Mirantis**
Mirantis的主要业务是提供开源软件OpenStack的订阅服务。借助Mirantis，企业云服务可以达到类似亚马孙、谷歌和微软的云服务的效果。该软件通常被认为是数据中心管理系统，可以提供软件平台帮助公司整体管理服务器系统、存储设备和网络设备。

**.NET**
.NET是Microsoft XML Web service平台。XML Web service 允许应用程序通过Internet进行通讯和共享数据，而不管所采用的是哪种操作系统、设备或编程语言。Microsoft.NET平台提供创建XML Web service并将这些服务集成在一起之所需。


