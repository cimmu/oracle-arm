# oracle-arm
Oracle cloud arm server auto-snap script 甲骨文乌龟壳自动抢ARM脚本
![visitors](https://visitor-badge.glitch.me/badge?page_id=cimmu.oracle-arm)

# 本脚本优点

简单,主机配置好 oci config，然后下载 main.tf 即可，不用自己解析各种参数,自动设置ssh登陆密码。

oci 请求几乎无延迟（为了保险起见加了10s的间隔，会自动判断请求返回值动态调整请求时间）.

自动获取开机的**公网IP**，无需登陆后台即可ssh上🐔。

[点击查看完整使用教程](https://blog.iyume.top/other/136.html)

2022年5月6号首尔ARM开机成功

![image](https://user-images.githubusercontent.com/92285183/167255224-bbc640ac-f928-4a05-9688-143398062b8c.png)
