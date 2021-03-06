# 机型
> 我们已于2019年5月后上线的全新的主机创建流程，所含机型均为V2.0。
> - 如需了解V1.0版机型信息请[查看](uhost/introduction/uhost/type) 
> - 如需V2.0与V1.0概念相比发生了哪些变化，请[查看](uhost/faq#主机机型概念10和20发生了哪些变化)

UCloud云主机根据 **应用场景** 将主机区分为以下四种：

|  类别  | 特点 | 适用场景 |
|  :- | :- | :- |
| 快杰型 O | 计算、存储、网络性能卓越的最新一代云主机 | 数据库，MMO游戏，人工智能等 |
| 通用型 N | 配置自由灵活，选择丰富 | 企业级应用，内存服务，数据分析等 |
| 高主频型 C | 采用3.2GHz主频的CPU，计算性能强 | 高频交易，数据处理，图形渲染等 |
| GPU型 G | 搭载K80，P40或V100 GPU | 人工智能，科学计算，图形渲染等 |

?> 想了解全部价格？查看 [主机价格](https://docs.ucloud.cn/uhost/price)



# 机型
> 我们已于2019年5月后上线全新的主机创建流程，所含机型均为V2.0。
> - 如需了解V1.0版机型信息请[查看](uhost/introduction/uhost/type) 
> - 如需了解V2.0与V1.0的的版本对比，请[查看](uhost/faq#主机机型概念10和20发生了哪些变化)

## 1. 快杰型 O
计算、存储与网络性能卓越的最新一代云主机。适合全面需求场景
- **CPU平台支持** Intel Cascadelake / AMD EPYC2
- **CPU内存组合** 支持配比1:1-1:8
- **磁盘类型** RSSD云盘
- **特性支持** 网络增强2.0和热升级

?> 想了解全部价格？查看 [主机价格](https://docs.ucloud.cn/uhost/price)

!> **限制** ：快杰型云主机仅支持高内核版本镜像。若希望使用现有镜像创建快杰型云主机，请联系技术支持。

### CPU内存组合

| CPU | 内存                 |
|  :- | :- | 
| 4核  | 4G，8G，16G，32G      |
| 8核  | 8G，16G，32G，64G     |
| 16核 | 16G，32G，64G，128G   |
| 32核 | 32G，64G，128G, 256G |
| 64核 | 64G，128G，256G, 512G   |
| 96核 | 96G，192G，384G, 764G  |

### 磁盘类型

| 系统盘              | 数据盘                |
|  :- | :- |
| RSSD云盘 (20-500GB) | RSSD云盘（20-32000GB） |



## 2. 通用型 N
> 提供最灵活自由的CPU、内存、磁盘组合。适合计算、存储、网络等均衡的场景
> - **CPU平台支持** Intel IvyBridge/Haswell/Broadwell/Skylake
> - **CPU内存组合** 支持配比1:1-1:8
> - **磁盘类型** 云盘、普通本地盘、SSD本地盘
> - **特性支持** 网络增强1.0/网络增强2.0（仅Skylake及以上支持）和热升级

?> 查看 [价格](https://docs.ucloud.cn/uhost/price) ｜ 了解 [磁盘](/uhost/introduction/disk) ｜了解 [特性简介：网络增强、热升级与数据方舟](/uhost/introduction/uhost/feature) ｜ 了解 [CPU平台](https://leaishere.github.io/UDocs_Templates_online-demo/#/type_online)


### CPU内存组合 

| CPU | 内存                         |
|  :- | :- | 
| 1核  | 1G，2G，4G，8G                |
| 2核  | 2G，4G，6G，8G，12G，16G        |
| 4核  | 4G，6G，8G，12G，16G，32G       |
| 8核  | 8G，12G，16G，24G，32G，48G，64G |
| 16核 | 16G，24G，32G，48G，64G，128G   |
| 24核 | 24G，32G，64G，96G，192G       |
| 32核 | 32G，64G，96G，128G           |

### 磁盘类型支持 

| 系统盘              | 数据盘                              |
|  :- | :- | 
| SSD云盘 (20-500GB) | SSD云盘（20-4000GB），普通云盘（20-8000GB） |
| 普通本地盘（20-100GB）  | 普通本地盘（20-2000GB）                 |
| SSD本地盘（20-100GB） | SSD本地盘（20-1000GB）                |



## 3. 高主频型 C
> CPU主频≥3.0GHz的机型，适合计算类业务，如高频交易、渲染、人工智能等
> - **CPU平台支持** Intel Skylake
> - **CPU内存组合** 支持配比1:1-1:8
> - **磁盘类型** 云盘、SSD本地盘
> - **特性支持** 网络增强1.0和热升级

?> 查看 [价格](https://docs.ucloud.cn/uhost/price) ｜ 了解 [磁盘](/uhost/introduction/disk) ｜了解 [特性简介：网络增强、热升级与数据方舟](/uhost/introduction/uhost/feature) ｜ 了解 [CPU平台](https://leaishere.github.io/UDocs_Templates_online-demo/#/type_online)

### CPU内存组合

| CPU | 内存               |
|  :- | :- | 
| 1核  | 1G，2G，4G，8G      |
| 2核  | 2G，4G，8G，16G     |
| 4核  | 4G，8G，16G，32G    |
| 8核  | 8G，16G，32G，64G   |
| 16核 | 16G，32G，64G，128G |
| 32核 | 32G，64G，128G     |

### 磁盘类型支持

| 系统盘              | 数据盘                              |
|  :- | :- | 
| SSD云盘 (20-500GB) | SSD云盘（20-4000GB），普通云盘（20-8000GB） |
| SSD本地盘（20-100GB） | SSD本地盘（20-1000GB）                |



## 4. GPU型 G
> 附带GPU卡的机型，适合需要GPU进行计算的业务，如高性能运算、渲染、人工智能等。目前支持K80, P40, V100
3种GPU卡。三种卡附属的配置略有不同

?> 查看 [价格](https://docs.ucloud.cn/uhost/price) ｜ 了解 [磁盘](/uhost/introduction/disk) ｜了解 [特性简介：网络增强、热升级与数据方舟](/uhost/introduction/uhost/feature) ｜ 了解 [CPU平台](https://leaishere.github.io/UDocs_Templates_online-demo/#/type_online)

### GPU性能对比

| 参数       | Tesla V100 | Tesla P40 | Tesla K80  |
|  :- | :- | :- | :- |
| CUDA核心数  | 5120       | 3840      | 2496       |
| 单精度浮点性能  | 14 TFOPS   | 12 TFLOPS | 8.7 TFLOPS |
| INT8性能   | N/A        | 47 TOPS   | N/A        |
| Tensor性能 | 112 TFLOPS | N/A       | N/A        |
| 显存容量     | 16GB       | 24GB      | 12GB       |
| 架构       | Volta      | Pascal    | Kepler     |

## 5. V100 / P40 GPU
> 简介……
> - **CPU平台支持** Broadwell
> - **CPU内存组合** 
> - **磁盘类型** 云盘、SSD本地盘
> - **特性支持** 网络增强1.0

?> 查看 [价格](https://docs.ucloud.cn/uhost/price) ｜ 了解 [磁盘](/uhost/introduction/disk) ｜了解 [特性简介：网络增强、热升级与数据方舟](/uhost/introduction/uhost/feature) ｜ 了解 [CPU平台](https://leaishere.github.io/UDocs_Templates_online-demo/#/type_online)

#### GPU-CPU-内存组合支持

| GPU | CPU | 内存       |
|  :- | :- | :- |
| 1颗  | 4核  | 8G，16G   |
|     | 8核  | 16G，32G  |
| 2颗  | 8核  | 16G，32G  |
|     | 16核 | 32G，64G  |
| 4颗  | 16核 | 32G，64G  |
|     | 32核 | 64G，128G |

### 磁盘类型支持

| 系统盘              | 数据盘                              |
|  :- | :- |
| SSD云盘 (20-500GB) | SSD云盘（20-4000GB），普通云盘（20-8000GB） |
| SSD本地盘（20-100GB） | SSD本地盘（20-1000GB）                |


## 6. K80 GPU
> 简介……
> - **CPU平台支持** Intel Haswell
> - **CPU内存组合** 
> - **磁盘类型** SSD本地盘
> - **特性支持** 网络增强1.0

?> 查看 [价格](https://docs.ucloud.cn/uhost/price) ｜ 了解 [磁盘](/uhost/introduction/disk) ｜了解 [特性简介：网络增强、热升级与数据方舟](/uhost/introduction/uhost/feature) ｜ 了解 [CPU平台](https://leaishere.github.io/UDocs_Templates_online-demo/#/type_online)

### GPU-CPU-内存组合支持

| GPU   | CPU | 内存      |
|  :- | :- | :- |
| 1颗/2颗 | 4核  | 8G，16G  |
| 1颗/2颗 | 8核  | 16G，32G |
| 1颗/2颗 | 16核 | 32G，64G |

### 磁盘类型支持

| 系统盘              | 数据盘               |
|  :- | :- |
| SSD本地盘（20-100GB） | SSD本地盘（20-1000GB） |


