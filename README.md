极路由一键安装SS脚本

脚本内需要设定安装包的URL根地址；

SSR已经很久没有更新了，这里找不到合适的包「里面需要包含极路由的LUCI才可以」

SSR和PDNSD一起协同工作，如果要更新GFWLIST，可使用这个命令，自己进行修改：

cd /etc/shadows地址 && wget https://raw.githubusercontent.com/gfwlist/gfwlist/master/gfwlist.txt && cat gfw.txt >> gw-shadowsocks.dnslist && /etc/init.d/dnsmasq restart

更多东西需要大家一起协助完善；
