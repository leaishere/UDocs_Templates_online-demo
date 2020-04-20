# 主机
## 创建主机
### 1. 在UHost管理控制台左上方区域点击“创建主机”，出现创建主机向导：
![](/images/create_uhost01.png)
### 2. 选择地域/可用区，不同地域/可用区下的云主机可选配置稍有差异；
![](/images/create_uhost02.png)
### 3. 选择系列、机型、CPU、内存、镜像与磁盘配置；
![](/images/create_uhost03.png)
### 4. 选择所属VPC、所属子网、是否绑定外网弹性IP以及防火墙设置（绑定外网弹性IP可后续另行配置）；
![](/images/create_uhost04.png)
### 5. 选择所属业务组，设置主机名称与管理员密码；
![](/images/create_uhost05.png)
### 6. 选择购买数量和付费方式，点击“立即购买”，进入支付确认页面；或选择“加入清单”，稍后购买；
### 7. 在支付确认页面，对您所购买的资源和账户余额进行最终确认，无误后点击“确认支付”；
### 8. 回到云主机的资源列表页，您可以看到该台主机在“初始化”中，通常在分钟级别内，主机即可创建完成。
### 9. 更多详情参见[云主机快速上手指南](uhost/newuser/briefguide)

> 为了使客户获得更优质的体验，UCloud控制台不再支持IE9及以下版本的浏览器；
> 使用终端完成操作后，请注意在操作系统内退出登录，当然超过默认退出时间，系统也会自动退出登录。

## 各地域NTP配置操作指南
| 地域    | 可用区  | NTP服务器1       | NTP服务器2       | NTP服务器3           |
| ----- | ---- | ------------- | ------------- | ----------------- |
| 北京一   | 可用区A | 10.255.255.1  | 10.255.255.2  | 0.cn.pool.ntp.org |
| 北京二   | 可用区B | 10.9.255.1    | 10.9.255.2    | 0.cn.pool.ntp.org |