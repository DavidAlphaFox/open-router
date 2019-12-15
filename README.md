# open-router
OpenBSD software router

## 说明

em0 为连接光猫的网口

vether 为内网虚拟网口，指定了IP地址和网络掩码

vether和em1～em5构成网桥，用来连接内网完成转发和路由任务

## 依赖的包

miniupnpd 用来完成upnp动态映射

dhcpd 系统默认安装，用来给局域网分配IP地址
