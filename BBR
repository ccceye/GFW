# 开启BBR拥塞控制算法

开启BBR，需要内核版本在Linux kernel 4.9以上

开机后 uname -r 看看是不是内核4.9、4.10或4.11

执行 lsmod | grep bbr，如果结果中没有 tcp_bbr 的话就先执行

### 开启bbr

> echo "net.core.default_qdisc=fq" >> /etc/sysctl.conf

> echo "net.ipv4.tcp_congestion_control=bbr" >> /etc/sysctl.conf

保存生效

> sysctl -p

### 关闭bbr

> sed -i '/net\.core\.default_qdisc=fq/d' /etc/sysctl.conf && sed -i '/net\.ipv4\.tcp_congestion_control=bbr/d' /etc/sysctl.conf

> sysctl -p

