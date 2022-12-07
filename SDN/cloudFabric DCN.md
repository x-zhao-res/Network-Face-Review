### cloudFabric DCN层次

#### 业务呈现/协同层

实现网络编排、业务发放、计算/存储资源和网络资源的协同调度。可使用对接云平台、客户自有应用Portal、Agile Controller-DCN界面实现业务协同调度

> 使用平台为openstack、FusionSphere

#### 网络控制层

实现物理和虚拟网络的统一控制

北向支持与云平台标准对接，或直接进行业务编排、网络建模和网络业务自动化部署。南向支持OpenFlow、OVSDB、NetConf等标准接口，管理控制物理和虚拟网络设备

> 主要使用Agile Controller

#### 网络服务层

支持基于Network/Hybird/Host Overlay VXLAN的Fabric、网络设备堆叠、M-LAG组网、双活VXLAN网关和L4-L7业务自动化

#### 计算接入层

承担计算和存储资源池的职责，同时支持主流虚拟化平台的裸金属服务器自动化发放。