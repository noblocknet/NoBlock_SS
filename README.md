极路由一键安装SS脚本

脚本内需要设定安装包的URL根地址；

SSR已经很久没有更新了，这里找不到合适的包「里面需要包含极路由的LUCI才可以」

SSR和PDNSD一起协同工作，需要更新GFWLIST才可以工作，可是使用这个命令来更新：

cd /etc/gw-redsocks/gw-shadowsocks && wget https://raw.githubusercontent.com/gfwlist/gfwlist/master/gfwlist.txt && cat gfw.txt >> gw-shadowsocks.dnslist && /etc/init.d/dnsmasq restart

更多东西需要打开一起协助完善；
