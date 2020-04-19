OpenWrt 编译 LuCI ---> Applications 添加插件应用说明
=========================

**make menuconfig  进入定制界面**\
进入编译选项配置界面,.按照需要配置.( ‘*’ 代表编入固件，‘M’ 表示编译成模块或者IPK包， ‘空’不编译 )

选择LuCI 配置 添加插件应用：常用

-----------------------------------------------------------------------------------------
* LuCI ---> Applications ---> luci-app-accesscontrol   `#访问时间控制`
* LuCI ---> Applications ---> luci-app-adbyby-plus    `#广告屏蔽大师plus +`
* LuCI ---> Applications ---> luci-app-arpbind   `#IP/MAC绑定`
* LuCI ---> Applications ---> luci-app-autoreboot   `#支持计划重启`
* LuCI ---> Applications ---> luci-app-ddns    `#动态域名 DNS（集成阿里DDNS客户端）`
* LuCI ---> Applications ---> luci-app-filetransfer   `#文件传输（可web安装ipk包）`
* LuCI ---> Applications ---> luci-app-firewall    `#添加防火墙`
* LuCI ---> Applications ---> luci-app-flowoffload   `#turbO ACC网络加速（集成FLOW,BBR,NAT,DNS...`
* LuCI ---> Applications ---> luci-app-frpc    `#内网穿透 frp`
* LuCI ---> Applications ---> luci-app-guest-wifi   `#WiFi访客网络`
* LuCI ---> Applications ---> luci-app-ipsec-virtual**d   `#virtual**服务器 Ipsec`
* LuCI ---> Applications ---> luci-app-mwan3    `#MWAN3负载均衡`
* LuCI ---> Applications ---> luci-app-mwan3helper    `#MWAN3分流助手`
* LuCI ---> Applications ---> luci-app-nlbwmon    `#网络带宽监视器`
* LuCI ---> Applications ---> luci-app-ramfree   `#释放内存`
* LuCI ---> Applications ---> luci-app-samba    `#网络共享（samba）`
* LuCI ---> Applications ---> luci-app-sqm   `#流量智能队列管理（QOS）`
-------------------------------------------------------------------------------------------
* LuCI ---> Applications ---> luci-app-SSR-plus    `#SSR低调上网plus+`
  -  luci-app-SSR-plus ---> Include ss v2ray Plugin   `#Ss v2ray插件   *`
  -  luci-app-SSR-plus ---> Include v2ray   `#v2ray代理`
  -  luci-app-SSR-plus ---> Include Trojan   `#trojan代理`
  -  luci-app-SSR-plus ---> Include red-socks2   `#red-socks2代理   *`
  -  luci-app-SSR-plus ---> Include Kcptun   `#kcptun加速`
  -  luci-app-SSR-plus ---> Include 违禁软件 Server   `#SSR服务器`
-------------------------------------------------------------------------------------------
* LuCI ---> Applications ---> luci-app-syncdial   `#多拨虚拟网卡（原macvlan）`
* LuCI ---> Applications ---> luci-app-unblockmusic   `#解锁网易云灰色歌曲3合1新版本`
* LuCI ---> Applications ---> luci-app-upnp    `#通用即插即用uPnP（端口自动转发）`
* LuCI ---> Applications ---> luci-app-vlmcsd   `#KMS服务器设置`
* LuCI ---> Applications ---> luci-app-vsftpd   `#FTP服务器`
* LuCI ---> Applications ---> luci-app-wifischedule   `#WiFi 计划`
* LuCI ---> Applications ---> luci-app-wirele违禁软件egdb   `#WiFi无线`
* LuCI ---> Applications ---> luci-app-wol    `#WOL网络唤醒`
* LuCI ---> Applications ---> luci-app-wrtbwmon   `#实时流量监测`
* LuCI ---> Applications ---> luci-app-xlnetacc   `#迅雷快鸟`
* LuCI ---> Applications ---> luci-app-zerotier   `#zeRotier内网穿透`
* Extra packages  --->  ipv6helper   `#支持 ipv6`
* Utilities  --->  open-vm-tools   `#打开适用于vmwarE的VM tools`


***以下是全部：***                         注：应用后面标记 “ * ” 为最近新添加

-----------------------------------------------------------------------------------------
* LuCI ---> Applications ---> luci-app-accesscontrol   `#访问时间控制`
* LuCI ---> Applications ---> luci-app-acme   `#ACME自动化证书管理环境`
* LUCI ---> Applications ---> luci-app-adblock    `#ADB广告过滤`
* LUCI ---> Applications ---> luci-app-adbyby-plus   `#广告屏蔽大师plus +`
* ~~LUCI ---> applications ---> luci-app-adbyby    `#广告过滤大师（已弃）`~~
* ~~LUCI ---> applications ---> luci-app-adkill    `#广告过滤（已弃）`~~
* LUCI ---> Applications ---> luci-app-advanced-reboot   `#linksys高级重启`
* LUCI ---> Applications ---> luci-app-ahcp   `#支持AHcPd`
* LUCI ---> Applications ---> luci-app-airplay2    `#aIrplay音乐推流(安卓+IOS)   *`
* LUCI ---> Applications ---> luci-app-aliddns    `#阿里DDNS客户端（已弃，集成至ddns）`
* LUCI ---> Applications ---> luci-app-amule   `#amule下载工具`
* LUCI ---> Applications ---> luci-app-aria2  `# aria2下载工具`
* LUCI ---> Applications ---> luci-app-arpbind   `#IP/MAC绑定`
* LUCI ---> Applications ---> luci-app-asterisk   `#支持asterisk电话服务器`
* LUCI ---> Applications ---> luci-app-attendedsysupgrade   `#固件更新升级相关`
* LUCI ---> Applications ---> luci-app-autoreboot   `#支持计划重启`
* LUCI ---> Applications ---> luci-app-baidupcs-web   `#百度网盘管理`
* LUCI ---> Applications ---> luci-app-bcp38   `#BCP38网络入口过滤（不确定）`
* LUCI ---> Applications ---> luci-app-bird1-ipv4   `#对bird1-ipv4的支持`
* LUCI ---> Applications ---> luci-app-bird1-ipv6   `#对bird1-ipv6的支持`
* ~~LUCI ---> applications ---> luci-app-bird4    `#bird 4（未知）（已弃）`~~
* ~~LUCI ---> applications ---> luci-app-bird6    `#bird 6（未知）（已弃）`~~
* LUCI ---> Applications ---> luci-app-bmx6   `#BMX6路由协议`
* LUCI ---> Applications ---> luci-app-bmx7   `#BMX7路由协议`
* ~~LUCI ---> applications ---> luci-app-caldav   `#联系人（已弃）`~~
* LUCI ---> Applications ---> luci-app-cifs-mount    `#CIFS/SMB挂载设置   *`
* LUCI ---> Applications ---> luci-app-cifsd   `#CIFS/SMB网络共享   *`
* LUCI ---> Applications ---> luci-app-cjdns   `#加密IPV6网络相关`
* LUCI ---> Applications ---> luci-app-clamav   `#clAMAV杀毒软件`
* LUCI ---> Applications ---> luci-app-commands    `#shell命令模块`
* LUCI ---> Applications ---> luci-app-cshark    `#cloUdshark捕获工具`
* LUCI ---> Applications ---> luci-app-ddns    `#动态域名 DNS（集成阿里DDNS客户端）`
* LUCI ---> Applications ---> luci-app-diag-core    `#core诊断工具`
* LUCI ---> Applications ---> luci-app-diskman    `#磁盘管理工具   *`
    - luci-app-diskman ---> Include btrfs-progs    `#新型的写时复制 (COW)`
    - luci-app-diskman ---> Include lsblk    `#lsblk命令 用于列出所有可用块设备的信息`
    - luci-app-diskman ---> Include mdadm    `#mdadm命令 用于创建、管理、监控RAID设备的工具`
    - luci-app-diskman ---> Include kmod-md-raid456    `#RAID 4,5,6 驱动程序模块`
    - luci-app-diskman ---> Include kmod-md-linear    `#RAID 驱动程序模块`
* LUCI ---> Applications ---> luci-app-dnscrypt-proxy   `#DNscrypt解决DNS污染`
* LUCI ---> Applications ---> luci-app-dnsforwarder   `#DNsforwardeR防DNS污染`
* ~~LUCI ---> applications ---> luci-app-dnspod   `#dnspod动态域名解析（已弃）`~~
* LUCI ---> Applications ---> luci-app-dockerman   `#docker容器`
* LUCI ---> Applications ---> luci-app-dump1090   `#民航无线频率（不确定）`
* LUCI ---> Applications ---> luci-app-dynapoint   `#dyNapoint（未知）`
* LUCI ---> Applications ---> luci-app-e2guardian    `#web内容过滤器`
* LUCI ---> Applications ---> luci-app-familycloud    `#家庭云盘`
* LUCI ---> Applications ---> luci-app-filetransfer   `#文件传输（可web安装ipk包）`
* LUCI ---> Applications ---> luci-app-firewall    `#添加防火墙`
* LUCI ---> Applications ---> luci-app-flowoffload   `#turbO ACC网络加速（集成FLOW,BBR,NAT,DNS...`
* LUCI ---> Applications ---> luci-app-freifunk-diagnostics    `#freifunk组件 诊断（未知）`
* LUCI ---> Applications ---> luci-app-freifunk-policyrouting   `#freifunk组件 策略路由（未知）`
* LUCI ---> Applications ---> luci-app-freifunk-widgets   `#freifunk组件 索引（未知）`
* LUCI ---> Applications ---> luci-app-frpc    `#内网穿透frp客户端`
* LUCI ---> Applications ---> luci-app-frps    `#内网穿透frp服务端   *`
* LUCI ---> Applications ---> luci-app-fwknopd   `#firewalL knocK operator服务器`
* LUCI ---> Applications ---> luci-app-guest-wifi    `#WiFi访客网络`
* ~~LUCI ---> applications ---> luci-app-gfwlist    `#GFW域名列表（已弃）`~~
* LUCI ---> Applications ---> luci-app-haproxy-tcp    `#Haproxy负载均衡-TCP`
* LUCI ---> Applications ---> luci-app-hd-idle   `#硬盘休眠`
* LUCI ---> Applications ---> luci-app-hnet   `#homeneT status家庭网络控制协议`
* LUCI ---> Applications ---> luci-app-ipsec-virtual**d   `#virtual**服务器 Ipsec`
* LUCI ---> Applications ---> luci-app-kodexplorer   `#KOD可道云私人网盘`
* ~~LUCI ---> applications ---> luci-app-kooldns   `#virtual**服务器 ddns替代方案（已弃）`~~
* ~~LUCI ---> applications ---> luci-app-koolproxy   `#KP去广告（已弃）`~~
* LUCI ---> Applications ---> luci-app-lxc    `#LXC容器管理`
* LUCI ---> Applications ---> luci-app-meshwizard  `#网络设置向导`
* LUCI ---> Applications ---> luci-app-minidlna    `#完全兼容DLNA / uPnP-AV客户端的服务器软件`
* LUCI ---> Applications ---> luci-app-mjpg-streamer    `#兼容linuX-UVC的摄像头程序`
* LUCI ---> Applications ---> luci-app-mtwifi   `#MtWiFi驱动的支持`
* ~~LUCI ---> applications ---> luci-app-mmc-over-gpio    `#添加SD卡操作界面（已弃）`~~
* LUCI ---> Applications ---> luci-app-multiwan    `#多拨虚拟网卡（已弃，移至syncdial）`
* ~~LUCI ---> applications ---> luci-app-mwan    `#MWAN负载均衡（已弃）`~~
* LUCI ---> Applications ---> luci-app-music-remote-center    `#DAAP遥控音乐服务器   *`
* LUCI ---> Applications ---> luci-app-mwan3    `#MWAN3负载均衡`
* LUCI ---> Applications ---> luci-app-mwan3helper    `#MWAN3分流助手`
* LUCI ---> Applications ---> luci-app-n2n_v2    `#N2N内网穿透 N2n v2 virtual**服务`
* LUCI ---> Applications ---> luci-app-netdata   `#netdata实时监控（图表）`
* LUCI ---> Applications ---> luci-app-nfs    `#NFS网络共享   *`
* LUCI ---> Applications ---> luci-app-nft-qos   `#QOS流控 nftables版`
* ~~LUCI ---> applications ---> luci-app-ngrokc   `#ngrok 内网穿透（已弃）`~~
* LUCI ---> Applications ---> luci-app-nlbwmon    `#网络带宽监视器`
* LUCI ---> Applications ---> luci-app-noddos   `#nODDOS clients 阻止dDoS攻击`
* LUCI ---> Applications ---> luci-app-ntpc    `#NTP时间同步服务器`
* LUCI ---> Applications ---> luci-app-ocserv   `#opEnconnect virtual**服务`
* LUCI ---> Applications ---> luci-app-olsr   `#OLSR配置和状态模块`
* LUCI ---> Applications ---> luci-app-olsr-services   `#OLSR服务器`
* LUCI ---> Applications ---> luci-app-olsr-viz    `#OLSR可视化`
* LUCI ---> Applications ---> luci-app-openvirtual**   `#openvirtual**客户端`
* LUCI ---> Applications ---> luci-app-openvirtual**-server   `#易于使用的openvirtual**服务器 weB-UI`
* ~~LUCI ---> applications ---> luci-app-oscam    `#OSCAM服务器（已弃）`~~
* LUCI ---> Applications ---> luci-app-p910nd    `#打印服务器模块`
* LUCI ---> Applications ---> luci-app-pagekitec    `#pagekite内网穿透客户端`
* LUCI ---> Applications ---> luci-app-polipo   `#polipo代理(是一个小型且快速的网页缓存代理)`
* LUCI ---> Applications ---> luci-app-pppoe-relay   `#PpPoE NAT穿透 点对点协议（PPP）`
* ~~LUCI ---> applications ---> luci-app-p p t p-server   `#virtual**服务器 p p t p（已弃）`~~
* LUCI ---> Applications ---> luci-app-privoxy   `#privoxy网络代理(带过滤无缓存)`
* LUCI ---> Applications ---> luci-app-qbittorrent   `#BT下载工具（qbittorrent）`
* LUCI ---> Applications ---> luci-app-qos    `#流量服务质量(QoS)流控`
* LUCI ---> Applications ---> luci-app-radicale    `#cALDAV/caRDDAV同步工具`
* LUCI ---> Applications ---> luci-app-ramfree   `#释放内存`
* LUCI ---> Applications ---> luci-app-rp-pppoe-server   `#roarinG penguiN PpPoE server 服务器`
* LUCI ---> Applications ---> luci-app-samba    `#网络共享（samba）`
* LUCI ---> Applications ---> luci-app-samba4    `#网络共享（samba4）`
* LUCI ---> Applications ---> luci-app-sfe   `#turbO ACC网络加速（flowoffload二选一）`
* ~~LUCI ---> applications ---> luci-app-s-s    `#SS低调上网（已弃）`~~
* LUCI ---> Applications ---> luci-app-s-s-libes   `#Ss-libev服务端`
* LUCI ---> Applications ---> luci-app-shairplay   `#支持aIrplay功能`
* LUCI ---> Applications ---> luci-app-siitwizard   `#SIIT配置向导  SIIT-wizzard`
* LUCI ---> Applications ---> luci-app-simple-adblock   `#简单的广告拦截`
* ~~LUCI ---> applications ---> luci-app-smartdns   `#SMARTDNS本地服务器（已弃）`~~
* LUCI ---> Applications ---> luci-app-softethervirtual**   `#soFtether virtual**服务器  NAT穿透`
* LUCI ---> Applications ---> luci-app-splash   `#clienT-splash是无线MESH网络的一个热点认证系统`
* LUCI ---> Applications ---> luci-app-sqm   `#流量智能队列管理（QOS）`
* LUCI ---> Applications ---> luci-app-squid    `#squid代理服务器`
* LUCI ---> Applications ---> luci-app-SSR-plus    `#SSR低调上网plus+`
    - luci-app-SSR-plus ---> Include s-s New Version   `#新SS代理（已弃）`
    - luci-app-SSR-plus ---> Include s-s Simple-obfs Plugin   `#simple-obfs简单混淆工具（已弃）`
    - luci-app-SSR-plus ---> Include s-s v2ray Plugin   `#Ss v2ray插件   *`
    - luci-app-SSR-plus ---> Include v2ray   `#v2ray代理`
    - luci-app-SSR-plus ---> Include Trojan   `#trojan代理`
    - luci-app-SSR-plus ---> Include red---socks2   `#red---socks2代理   *`
    - luci-app-SSR-plus ---> Include Kcptun   `#kcptun加速`
    - luci-app-SSR-plus ---> Include 违禁软件 Server   `#SSR服务器`
    - luci-app-SSR-plus ---> Include DNS2SOCKS   `#DNS服务器（已弃）`
    - luci-app-SSR-plus ---> Include 违禁软件 Socks and Tunnel（已弃）
    - luci-app-SSR-plus ---> Include Socks Server   `#socks代理服务器（已弃）`
* ~~LUCI ---> applications ---> luci-APP-ssr-pro   `#ssr-pro（已弃）`~~
* LUCI ---> Applications ---> luci-app-SSRserver-python   `#违禁软件 python服务器`
* LUCI ---> Applications ---> luci-app-statistics   `#流量监控工具`
* LUCI ---> Applications ---> luci-app-syncdial   `#多拨虚拟网卡（原macvlan）`
* LUCI ---> Applications ---> luci-app-tinyproxy   `#tinyproxy是 HTTP(S)代理服务器`
* LUCI ---> Applications ---> luci-app-transmission    `#BT下载工具`
* LUCI ---> Applications ---> luci-app-travelmate   `#旅行路由器`
* LUCI ---> Applications ---> luci-app-ttyd    `#网页终端命令行`
* LUCI ---> Applications ---> luci-app-udpxy   `#udpxy做组播服务器`
* LUCI ---> Applications ---> luci-app-uhttpd   `#UHTtPD web服务器`
* LUCI ---> Applications ---> luci-app-unblockmusic   `#解锁网易云灰色歌曲3合1新版本`
    - UnblockNeteaseMusic Golang Version   `#golang版本   *`
    - UnblockNeteaseMusic NodeJS Version   `#noDEJS版本   *`
* LUCI ---> Applications ---> luci-app-unblockneteasemusic-go   `#解除网易云音乐（合并）`
* LUCI ---> Applications ---> luci-app-unblockneteasemusic-mini   `#解除网易云音乐（合并）`
* LUCI ---> Applications ---> luci-app-unbound   `#unbounD DNS解析器`
* LUCI ---> Applications ---> luci-app-upnp    `#通用即插即用uPnP（端口自动转发）`
* LUCI ---> Applications ---> luci-app-usb-printer    `#USB 打印服务器`
* LUCI ---> Applications ---> luci-app-v2ray-server    `#v2ray 服务器`
* LUCI ---> Applications ---> luci-app-v2ray-pro   `#v2ray透明代理（已弃，集成SSR）`
* LUCI ---> Applications ---> luci-app-verysync   `#微力同步`
* LUCI ---> Applications ---> luci-app-vlmcsd   `#KMS服务器设置`
* LUCI ---> Applications ---> luci-app-vnstat    `#Vnstat网络监控（图表）`
* LUCI ---> Applications ---> luci-app-virtual**bypass   `#virtual** bypaSswEBUI  绕过virtual**设置`
* LUCI ---> Applications ---> luci-app-vsftpd   `#FTP服务器`
* LUCI ---> Applications ---> luci-app-watchcat   `#断网检测功能与定时重启`
* LUCI ---> Applications ---> luci-app-webadmin   `#web管理页面设置`
* ~~LUCI ---> applications ---> luci-app-webshell   `#网页命令行终端（已弃）`~~
* LUCI ---> Applications ---> luci-app-wifischedule   `#WiFi 计划`
* LUCI ---> Applications ---> luci-app-wireguard   `#virtual**服务器 wiReguard状态`
* LUCI ---> Applications ---> luci-app-wirele违禁软件egdb   `#WiFi无线`
* LUCI ---> Applications ---> luci-app-wol    `#WOL网络唤醒`
* LUCI ---> Applications ---> luci-app-wrtbwmon   `#实时流量监测`
* LUCI ---> Applications ---> luci-app-xlnetacc   `#迅雷快鸟`
* LUCI ---> Applications ---> luci-app-zerotier   `#zeRotier内网穿透`


---------------------------------------------------------------------------------------------------

**支持 iPv6：**\
1、Extra packages  --->  ipv6helper  （选定这个后下面几项自动选择了）
* Network  --->  odhcp6c
* Network  --->  odhcpd-ipv6only
  - LUCI  --->  Protocols  --->  luci-proto-ipv6
  - LUCI  --->  Protocols  --->  luci-proto-ppp

**2、打开适用于VMware的VM Tools**\
Utilities  --->  open-vm-tools

**3、第二次编译：**
命令|说明
:----|:-----:
cd lede                                                    |# 进入LEDE目录
git pull                                                   |# 同步更新大雕源码
./scripts/feeds update -a && ./scripts/feeds install -a    |# 更新Feeds
rm -rf ./tmp && rm -rf .config                             |# 清除编译配置和缓存
make menuconfig                                            |# 进入编译配置菜单
make -jn V=99                                              |# 开始编译 n=线程数+1，例如4线程的I5填-j5
