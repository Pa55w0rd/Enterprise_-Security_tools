## 企业安全建设中用到的开源or“免费”的工具

跳到甲方工作也差不多两年了，参与部分企业安全建设工作，主要工作还是渗透和开源平台的建设和维护使用


在这种“甲方”的工作体会就是

1. 公司不是很重视安全这块，网络安全法出台，明确要求企业要做等保测评，招个人做吧

2. 没有资源，要钱没有，要人没有，好在研发的小伙伴和运维小伙伴比较支持工作

两年里，搭建了很多开源的系统，在这里分类了一下， 如果有更好的 **欢迎推荐**

安装和使用可以去看官方文档

有基础的python和php知识，进行简单二次开发，还有就是调试软件，开源的很多莫名其妙的bug

研发能力强的团队，可以深入甲方企业安全，贴近业务，定制化去开发

<!-- more -->
### 漏扫
- [nessus](https://www.tenable.com/downloads/nessus)（[Home版](https://www.tenable.com/products/nessus/activation-code)）
- openvas(在[kali中安装openvas](https://www.kali.org/tutorials/configuring-and-tuning-openvas-in-kali-linux/)，注意挂代 理，不然会很慢很慢和报错)
- awvs（破解版-52pojie）
- APPscan ([破解版](https://pan.baidu.com/s/1sjkDDi1#list/path=%2F))
- Burpsuite pro （破解版）
- [mobsf](https://github.com/MobSF/Mobile-Security-Framework-MobSF) (移动app客户端，支持ios，但是需要在mac上跑)
- Nmap/Zmap/masscan 端口扫描
### 漏洞管理
- [洞察insight](https://github.com/creditease-sec/insight)
- smef
- [Fuxi](https://github.com/jeffzh3ng/Fuxi-Scanner/)
- [DefectDojo](https://github.com/DefectDojo/django-DefectDojo)
### 项管
- jira
- 禅道
### src平台
- [SRCMS](https://github.com/martinzhou2015/SRCMS)
- [laravel-src](https://github.com/233sec/laravel-src)
### 资产管理/自动化运维
- [xunfeng](https://github.com/ysrc/xunfeng)
- AssetsView
- [蓝鲸bk-cmdb](https://github.com/Tencent/bk-cmdb)
- [OpsManage](https://github.com/bongmu/OpsManage)
- [Ansible](http://www.ansible.com.cn/)
- [Saltstack](https://docs.saltstack.com/en/latest/contents.html)
### soc
- sosrp
- w3a_SOC
- OpenSOC
- ossim
### 入侵检测/安全监控/流量回溯
- suricata(selks)
- bro
- ossec(wazuh)
- Security Onion
- OwlH
- Nethserver
- Snort
- OpenWIPS-NG
- moloch
- [同程-驭龙](https://github.com/ysrc/yulong-hids)
- [CloudWalker（牧云）现在只开放webshell查杀](https://github.com/chaitin/cloudwalker)
- Osquery
### web应用安全
- [ngx_lua_waf](https://github.com/loveshell/ngx_lua_waf)
- [openstar](https://github.com/starjun/openstar)
- [ModSecurity](https://github.com/SpiderLabs/ModSecurity/tree/nginx_refactoring)
- [openwaf](https://github.com/titansec/OpenWAF)
- [openRASP](https://github.com/baidu/openrasp)
- x-waf
- jxwaf
### 终端安全集中管理
- 360企业版
- 火绒企业安全
### 堡垒机
- [jumpserver](https://github.com/jumpserver/jumpserver)
- teleport
### 代码质量管理/代码审计
- sonar + jekins
- cobra
- VCG
- fortify(破解版，找到最新的规则是2018.3)
- RIPS/Seay源代码审计系统(PHP))
- Findbugs（JAVA）

### web日志审计
- 360星图
- [xlog](https://github.com/apxar/xlog)
- [lorg](https://github.com/jensvoid/lorg)
### 日志分析系统
- elk（es+logstash+kibana)
- [Kibana_Hanization(kibana汉化)](https://github.com/anbai-inc/Kibana_Hanization)
### 上网行为管理/准入/认证
- [packetfence](https://packetfence.org/)
- ikuai
- openldap
- [中央认证服务（CAS）](https://github.com/apereo/cas)
### 数据防泄漏
- opendlp
### 基线检查/加固
- [CIS](https://learn.cisecurity.org/benchmarks)
- [Lynis审计](https://github.com/CISOfy/lynis/)
- [WINSpect](https://github.com/A-mIn3/WINspect)
- [OpenSCAP](https://www.open-scap.org/)
### github泄露扫描
- [x-patrol](https://github.com/MiSecurity/x-patrol)
- [Hawkeye](https://github.com/0xbug/Hawkeye)
- [GSIL](https://github.com/FeeiCN/GSIL)
- [VKSRC/Github-Monitor](https://github.com/VKSRC/Github-Monitor)
### 目录索引系统/个人网盘/文件共享
- [zdir](https://github.com/helloxz/zdir)
- [nextcloud](https://nextcloud.com/)
- [Seafile社区版 ](https://www.seafile.com/product/private_server/)
- ownCloud
- OnionShare
- Pydio Cells
### 蜜罐
- [opencanary_web](https://github.com/p1r06u3/opencanary_web)
- [T-Pot](https://github.com/dtag-dev-sec/tpotce)
- [mhn](https://github.com/threatstream/mhn)
### 钓鱼
- [P神的phishing](https://github.com/p1r06u3/phishing)
- [mail_fishing](https://github.com/sdlchina/mail_fishing)
- [blackeye](https://github.com/thelinuxchoice/blackeye)
- [Gophish](https://github.com/gophish/gophish)
### API网关
- [GoKu-API-Gateway](https://github.com/eolinker/GoKu-API-Gateway)
- [Kong](https://konghq.com/faqs/)

### 其他
- [WebRange(docker管理平台)](https://github.com/apxar/xlog)
- [app-host（内网app发布）](https://github.com/pluosi/app-host)
- [AdvBox](https://github.com/baidu/AdvBox)
- [osquery](https://github.com/facebook/osquery)
- [PHP-SSO](https://github.com/liujiantaoliu/TT-SSO)
- [Scout(url监控平台)](https://github.com/HandsomeOne/Scout)
- [jxotp(SSH登陆双因素认证系统)](https://github.com/jx-sec/jxotp)
- [DOClever](https://github.com/sx1989827/DOClever)
- [lynis审计](https://github.com/CISOfy/lynis)
- [archer](https://github.com/jly8866/archer)
- [walle-web（代码部署平台）](https://github.com/meolu/walle-web)
- [apollo(配置中心)](https://github.com/ctripcorp/apollo)
- [长亭开源牧云cloudwalker（只有webshell检测部分）](https://github.com/chaitin/cloudwalker)
- [Nebula "星云"业务风控系统](https://github.com/threathunterX/nebula)
- 美团DBProxy数据库防火墙
- Linxu下 rkhunter/chkrootkit 
- Win下 pchunter/ 火绒剑/ PowerTool/ ProcessExplorer/ ProcessHacker/ autoruns/ OTL
- [Kaspersky](http://devbuilds.kaspersky-labs.com/devbuilds/KVRT/latest/full/KVRT.exe)
- [Fastir_Collector_win取证](https://github.com/jensvoid/lorg)
- [Fastir_Collector_Linux取证](https://github.com/SekoiaLab/Fastir_Collector_Linux)
- D盾 webshell查杀
- Sandboxie 个人版沙箱
- ClamAV


Github Pages：[www.pa55w0rd.club](www.pa55w0rd.club)
微信公众号：Pa55w0rd
