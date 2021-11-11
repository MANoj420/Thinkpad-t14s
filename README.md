# Thinkpad-t14s


## Change TCP BBR

### Load the BBR kernel module.
```echo "tcp_bbr" > /etc/modules-load.d/modules.conf
```echo "net.core.default_qdisc=fq" > /etc/sysctl.d/bbr.conf
```` echo "net.ipv4.tcp_congestion_control=bbr" >> /etc/sysctl.d/bbr.conf
