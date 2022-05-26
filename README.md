# Windows10 Penetration Suite Toolkit within Kali Linux
![image](https://img.shields.io/badge/Author-Makoto56-blueviolet.svg)  ![image](https://img.shields.io/badge/Release-v3.0-blue.svg)  ![image](https://img.shields.io/badge/Platform-Windows-red.svg) ![image](https://img.shields.io/badge/WSL-Kali-9cf.svg) ![image](https://img.shields.io/badge/Property-%E6%AD%A6%E5%99%A8%E5%BA%93-brightgreen.svg) ![image](https://img.shields.io/badge/Update-2022.04.05-ff69b4.svg)

**`2022.05.26 补充内容`**

	1. 全新制作全套虚拟机镜像，包含：
	
	   Windows 7 x64
	   Windows 8 x64
	   Windows 10 x64
	   Windows Server 2008 x64
	   Windows Server 2012 x64
	   Windows Server 2016 x64
	   Windows Server 2019 x64
	   Ubuntu 20 x64
	   
	   所有虚拟机镜像均安装：
	   7z
	   Microsoft Visual C++ 2008-2022 运行库
	   密钥或激活工具激活
	   
	   可供测试软件，环境搭建等用途。
	   虚拟机账号密码已备注在VMware说明栏处，请注意查看。
	   
	   下载链接：
	   链接：https://pan.xunlei.com/s/VN2xlbB9pxTo0bWdgdg5vXUtA1
	   提取码：fvp3
	   
**`2022.04.09 补充说明`**

	1. 火绒可能会拦截对外攻击行为，在测试exp的时候如果失败可以查看火绒日志看是否被拦截。
	   感谢“看那蔚蓝色的星球”反馈。

**`2022.04.05 更新说明`**

	1. 本集成环境是根据本人渗透工作和学习中的侧重点进行制作，不可能做到满足所有人的需求。
	2. 发布以来已历经3次更新，借鉴参考了很多朋友的有益意见及建议，在此表示感谢！
	3. 如果您有好的意见或者建议，请联系邮箱burpsuite@qq.com。
	
    遵循精益求精、尽善尽美的原则：
	
    - 1. 去除了部分长期未更新及效果不好的工具；
	- 2. 补充了部分之前未收纳的工具；
	- 3. 目录尽可能做到简洁分类，重建开始菜单及快捷启动索引；
    - 4. 升级部分软件为最新版；
    - 5. 升级系统补丁截止至2022.04.03；
    - 6. 优化系统，清理无用垃圾文件。
	
**`系统简介`**

    - 基于Win10 Workstation 21H2 x64 MSDN原版镜像制作；
    - 完整安装WSL Kali Linux 2022.1，并配置图形化模式；
    - 精简系统自带软件，美化字体及部分图标，适度优化；
    - 镜像容量74.5G，使用单磁盘文件存储，提升性能；
    - 建议运行环境：
      * vmware：16.0
      * 运行内存：8G
      * 固态硬盘：100G

**`制作声明：`**

    1. 所有的安装类软件均下载自软件对应的官方网站；
    2. 所有的绿色类软件均下载自果核剥壳。（https://www.ghxi.com/）；
    3. 所有的脚本类工具均下载自github。（https://github.com/）；
    4. 部分授权类工具（破解版）及优秀的渗透工具来自微信公众号分享；
    
       * 排名不分先后，同时也推荐大家关注，一起变得更强。
       
       雾晓安全、果核剥壳、归零安全、潇湘信安、学蚁致用、谢公子学安全、利刃藏锋、棉花糖网络安全圈、HACK技术沉淀营、无尾熊安全、T00ls、
       渗透攻击红队、洛米唯熊、雷石安全实验室、酒仙桥六号部队、InBug实验室、鸿鹄实验室、黑白之道、HACK之道、GobySec、Gcow安全团队、
       Gamma实验室、CobaltStrike实战、冰河技术、网络安全与黑客技术、QZ的安全悟道、菜鸟学信安、乌雲安全、白帽子飙车路、信安之路、chaosec、
       鸟哥谈安全、安全小飞侠、moonsec、系统安全运维、天驿安全、零组攻防实验室、lemonsec、橘猫学安全、Hacking黑白红、渗透xiao白帽、
       渗透安全团队、白帽子社区、HACK学习呀、猪猪谈安全、开普勒安全团队、吾爱破解论坛、WhITECat安全团队、寻云安全团队、Khan安全攻防实验室、
       Bypass、天億网络安全、关注安全技术、玄魂工作室、边界骇客、零度安全攻防实验室、WgpSec狼组安全团队、黑白天实验室、靶机狂魔、渗透云笔记、
       TeamsSix、hijackY、TimeLine Sec、重生信息安全、GobySec、Gcow安全团队、冰蚕实验室。
	 
    5. 本项目制作的初衷是帮助渗透新手快速搭建工作环境，工欲善其事，必先利其器；
    6. 本项目由于后期调试原因可能会遗留部分本人的信息，请直接忽视；
    7. 本项目坚决不接受也从未曾接受任何形式的赞助；
    8. 如果您有好的意见或者建议，请联系邮箱burpsuite@qq.com。
    
**`免责声明：`**

    1. 本镜像仅面向合法授权的企业安全建设行为，如您需要测试本镜像的可用性，请自行搭建靶机环境；
    2. 在使用本镜像进行检测时，您应确保该行为符合当地的法律法规，并且已经取得了足够的授权；
    3. 如您在使用本镜像的过程中存在任何非法行为，您需自行承担相应后果，作者将不承担任何法律及连带责任。
    
## `软件及工具介绍：`

**`1. 系统环境类：`**
    
    - Directx
    - Net Framework 3.5
    - Net Framework 4.72
    - Visual basic virtual machine
    - Microsoft C runtime library
    - Microsoft visual C++ 2005-2019
    - 集成常用字库

**`2. WindowsApp类：`**

    - WSL kali linux
    - Windows Terminal（已替换默认cmd）

**`3. 其他工具类 （C:\Softwares）：`**

    - aact: 激活工具（一键激活windows & office）
    - bandicam: 视频录制工具（注册版）
    - bandizip: 压缩工具
    - chrome: 99.0 绿色修改版
      * 主要集成插件:
        - adblock: 广告拦截工具
        - adobe acrobat：pdf工具
        - charset：修改网页编码工具
        - chrome 清理大师: chrome清理工具
        - editthiscookie: cookie编辑工具
        - fofa pro view：fofa工具
        - funnel search：google搜索工具
        - hackbar：hackbar
        - infinity：标签页工具
        - ip address and domain inf: ip&domain探测工具
        - ip whois: whois 探测工具
        - neater bookmarks: 书签管理工具
        - octotree: github资源树查看工具
        - onetab：标签管理工具
        - postwoman：接口调试工具
        - proxy switchyomega：代理切换工具
        - seoquake：网页统计工具
        - supercopy：超级复制
        - toolbox 常用工具: 集成常用小工具
        - wappalyzer：网页技术分析工具
        - whatruns：网页技术分析工具
        - yet another drag and go: 超链接拖拽新窗口打开
    - contextmenumanager：右键菜单管理工具
    - dism++: 系统调节工具
    - everything: 搜索工具（已禁用windows自带搜索）
    - fdm：下载工具
	- google earth：谷歌地球
	- hackbgrt：修改windows启动icon
    - honeyview: 看图工具
    - huorong: 杀毒工具（c:\penetration 为白名单）
    - icon：第三方图标包
    - iobit:
      * uninstaller: 卸载工具（注册版）
      * advanced systemcare: 优化清理工具（注册版）
      * smart defrag: 磁盘碎片整理工具（注册版）
    - mactype：字体管理工具（已修改系统默认字体为Mac苹方体）
    - maye: 快捷启动工具
	- meitu：美图秀秀
    - oldnewexplorer: 资源管理器调节工具
    - pcmaster: 系统调整工具
      * 已创建右键快捷菜单：
        - 在此处打开terminal终端
        - 在此处打开kali linux终端
        - 在此处打开notepad
        - 控制面板
        - 计算器
        - 注册表
	- pdf：极速pdf
    - potplayer: 视频播放工具
	- refresh：刷新图标缓存
    - snipaste: 截图工具
	- telegram：电报客户端
	- wps：wps去广告版
	- youdaodict：有道词典（注册版）（已集成离线翻译库）

**`4. 渗透测试类（C:\Penetration）：`**
    
    - 常用的python及csharp脚本类工具均配有start.bat。
      * 注明工具版本及更新时间
      * 注明依赖环境
      * 注明主要参数
      * 注明简要用法（给工具不给用法的都是耍流氓）
 
**`[+] AndroidTools 安卓工具:`**
    
    - apktool：apk反编译工具
    - dex2jar：dex打包工具
    - ldplayer：雷电安卓模拟器

**`[+] AntivirusTools 免杀工具：`**
    
    - avevasion：https://github.com/1y0n/av_evasion_tool
	- bypass-antivirus：免杀教程
    - charlotte：https://github.com/9emin1/charlotte
	- cool：https://github.com/ed1s0nz/cool
    - crossnet：https://github.com/dr0op/crossnet-beta
    - darkarmour：https://github.com/bats3c/darkarmour
    - shellcodeloader：https://github.com/knownsec/shellcodeloader
    - vmprotect: 加壳工具（商业加壳，生成exe体积大）
    - vprotect: 加壳工具（商业加壳，生成exe体积较大）
    - zhetian：遮天shellcode加载工具（https://github.com/yqcs/ZheTian）
    
**`[+] ConnectTools 连接工具:`**
    
    - anydesk
    - filezilla
    - finalshell
    - teamviewer
    - xmanager

**`[+] CrackTools 破解工具:`**
    
    - access password recovery: access 密码破解工具
    - archive password recovery: zip & rar 密码破解工具
    - office password recovery: office 密码破解工具
    - pdf password recovery: pdf 密码破解工具
    
**`[+] DatabaseTools 数据库工具:`**
    
    - navicat premium: 数据库连接管理工具
    - neo4j：neo4j数据库管理工具
    - sharp sql tools：mssql数据库利用工具
    - sqlite：sqlite数据库管理工具
    - sqlknife：mssql数据库利用工具
    - sqlmap: 注入工具
    - sylas：mssql & orcle & postgresql数据库利用工具
    - toad：oracle数据库管理工具

**` [+] DictionaryTools 字典工具:`**
    
    - mutoudic：木头字典生成工具（注册版）
    - pentestdicts：https://github.com/ppbibo/pentesterspecialdict
    - pwdbud：字典生成工具（https://github.com/ort4u/PwdBUD）

**` [+] DiskTools 磁盘工具:`**
    
    - diskgenius: 专业版（可恢复硬盘数据）
    - ssdfresh：ssd优化工具

**`[+] EditTools 编辑工具:`**
    
    - 010editor: 十六进制编辑工具（注册版）
    - alldup：重复文件搜索工具
    - batchren: 批量重命名工具
    - beyond compare：文件对比工具
    - ctfcrack: 米斯特安全团队工具
    - findstr: 文本检索工具
    - jd-gui: java查看编辑工具
    - jsonview: json查看编辑工具
    - log parse：windows日志分析工具
    - log parse lizard：windows日志分析工具（图形化）
    - notepad++: 编辑工具
      * 添加右键菜单：使用Notepad编辑
    - pst converter：pst邮件转换工具
    - rapid environment: 环境变量编辑工具
    - sharp sword：csharp版本word查看工具
    - sublime: 编辑工具（注册版）
      * 添加右键菜单：使用Sublime编辑
    - xmind：思维导图工具

**`[+] ExpolitTools 漏洞工具:`**
    
    - cms hunter:https://github.com/SecWiki/CMS-Hunter
    - exphub：https://github.com/zhzyker/exphub
    - middleware-vulnerability-detection：https://github.com/mai-lang-chai/middleware-vulnerability-detection
    - system-vulnerability：https://github.com/mai-lang-chai/system-vulnerability
    - vulmap：web漏扫验证工具（https://github.com/zhzyker/vulmap）
    - vulnerability：https://github.com/edgesecurityteam/vulnerability
    - 更多漏洞exp见 c:\Penetration\ExpolitTools（漏洞exp较多，请善用everything搜索）

**`[+] IntranetTools 内网工具:`**
    
    - abptts：内网穿透工具
    - add user: 添加用户工具
    - ad explore：ldap工具
    - blood hound：域渗透分析工具
    - defeat defender：关闭defender工具
    - dismap：内网漏洞扫描工具
    - domain tools：域渗透工具
    - earth worm: 内网穿透工具
    - frp: 内网穿透工具（https://github.com/fatedier/frp）
    - fscan：内网扫描工具（https://github.com/shadow1ng/fscan）
    - homework of powershell：3gstudent powershell工具
    - hydra: 口令爆破工具
    - impacket：内网协议工具（https://github.com/SecureAuthCorp/impacket）
    - invoke-obfuscation：powershell工具（https://github.com/danielbohannon/Invoke-Obfuscation）
    - kscan：内网扫描工具（https://github.com/lcvvvv/kscan）
    - ladon：内网扫描工具（小密圈9.1.4版本）
    - lcx：端口转发工具
    - ldap admin：ldap工具
    - mimikatz：密码抓取工具（文件夹下集成下列密码抓取工具）
      * gosecretsdump
      * hklm
      * kekeo
      * lazagne
      * mimipenguin
      * ntdsdumpex
      * procdump
      * pwdump
      * quarkspw dump
    - nc: 监听工具
    - neo-regeorg：regeorg改良版（https://github.com/L-codes/Neo-reGeorg）
    - openrdp：开启远程桌面工具
    - pe：冰封pe iso镜像
    - powershdll：powershell工具
    - ps2exe：powershell转exe工具
    - pstools：微软官方psexec工具
    - reverseshell：反弹shell工具
    - revsh：内网穿透工具（https://github.com/emptymonkey/revsh）
    - scrun：k8 shellcode加载工具
    - sharp tools：
      * sharp adi dnsdump：域dns枚举工具
      * sharp decrypt pwd：浏览器密码解密工具
      * sharp event log：日志分析工具
      * sharp hound：域渗透分析工具
      * sharp net check：出网探测工具
    - socks over rdp：rdp协议内网穿透工具
    - spp：内网穿透工具（https://github.com/esrrhs/spp）
    - stowaway：内网穿透工具（https://github.com/ph4ntonn/Stowaway）
    - wce：windows凭证编辑工具
    - wget：下载工具
    - wmihacker：wmi渗透工具
    - xray：扫描工具（https://github.com/chaitin/xray）
    - 更多内网工具见 C:\Penetration\IntranetTools

**`[+] OfficeTools 办公工具：`**
    
    - adobe acrobat dc 2020：PDF编辑工具
    - adobe audition 2020：音频编辑工具
    - adobe photoshop 2020：图片编辑工具
    - office 六件套: word + excel + powerpoint + access + onenote + outlook
    - wps三件套：word + excel + powerpoint

**`[+] ProgramTools 编程工具：`**
   
    - golang
    - java：
      * jre1.8.0：已配置环境变量，系统默认调用java8
      * openjdk15.0.2：绿色版，如有特殊软件需要java15环境运行可直接调用/bin/java.exe即可
    - python：
      * python2：python2命令启动（python2 test.py）
      * python3：python3命令启动（python3 test.py）
      * 已集成本镜像所有python3工具的pip依赖库
      * 使用pip命令调用python3 pip
    - tdm gcc
    - visual studio 2015

**`[+] ReverseTools 逆向工具：`**
    
    - dnspy：csharp逆向工具
    - exescope：exe编辑工具
    - green helper：exe绿化工具
    - olly debug：exe调试工具
    - peidtool：查壳工具
    - signtool：签名伪造工具
    - upxshell：upx加壳工具
    - x64dbg：exe调试工具

**`[+] ScanTools 扫描工具:`**
    
    - acunetix: web vulnerability scanner 14.7.220401065（注册版）（可扫描Log4j & spring core rce）
      * user: admin@awvs.com
      * pass: Admin@awvs.com
    - appscan：app scan 10.0.7（注册版）
    - nmap：端口扫描工具
    - router scan: C段扫描工具
    - snet cracker: 弱口令扫描工具
    - scan box:
      * avscan 杀毒软件检测工具：
        - checkav
      * leakscan 敏感文件扫描工具：	
        - dirmap：https://github.com/H4ckForJob/dirmap
        - dirsearch：https://github.com/maurosoria/dirsearch
        - packerfuzzer：https://github.com/rtcatc/Packer-Fuzzer
        - scantools：https://gitee.com/windyjxx/ScanTools
        - yujian
        - githack
        - ...
      * subdomain 子域名探测工具：
        - fofa view：fofa查询工具
        - oneforall：https://github.com/shmilylty/OneForAll
        - securitytrails
        - sublist3r：https://github.com/aboul3la/Sublist3r
        - subfinder：https://github.com/projectdiscovery/subfinder
        - webtitle
        - domaininfo
        - webbatchrequest
        - ...
    - 更多扫描工具见 C:\Penetration\ScanTools\ScanBox（其中scanbox项目 https://github.com/we5ter/scanners-box）

**`[+] ShellTools 权限工具:`**
    
    - antsword: 蚁剑（已集成插件）（https://github.com/AntSwordProject/AntSword-Loader）
    - behinder: 冰蝎（shell密码统一为cmd）（https://github.com/rebeyond/Behinder）
      * behinder 2.0.1
      * behinder 3.0 beta11
      * behinder 3.3.2修改版（https://github.com/angels520/rebeyond-Mode）
    - cobaltstrike: 4.4汉化版
      * 使用csagent汉化（https://github.com/Twi1ight/CSAgent）
      * 去除cobaltstrike特征（修改端口 + 重签证书 + random.profile）
      * vps启动teamserver：./teamserver ip port random.profile
      * 集成插件：（C:\Penetration\ShellTools\CobaltStrike\scripts）
        - adcollection
        - bypassav
        - erebus
        - eval
        - eventlogmaster
        - ladon
        - mikasa
        - taowu
	- gbbypass：jsp免杀工具（https://github.com/czz1233/GBByPass）
    - godzilla：哥斯拉（密码为默认pass + key）（https://github.com/BeichenDream/Godzilla）
    - kali：wsl kali linux 2022.1
      * 用户：
        - user：kali pass：kali
        - user：root pass：root
      * 修改软件源为阿里云 + 清华大学
      * 完整安装kali linux所有软件包
      * 安装xrdp服务，可用rdp客户端打开kali linux图形化模式
        - kali命令行模式下运行/home/kali/xrdp-restart.sh打开xrdp服务，即可使用rdp登录kali
        - rdp配置：127.0.0.1:3390
        - kali命令行模式下运行/home/kali/xrdp-stop.sh关闭xrdp服务
        - 如果不需要使用图形化模式，建议关闭xrdp服务（非常占用资源）
    - pyshell：python版shell管理工具（https://github.com/JoelGMSec/PyShell）
    - skyscorpion：天蝎（shell密码统一为cmd）（https://github.com/shack2/skyscorpion）
    - shell:免杀一句话木马（密码统一为cmd）
    - webshell: webshell收集项目（https://github.com/tennc/webshell）

**`[+] StegaTools 隐写工具：`**

    - beyond compare：对比工具
    - binwalk：分解工具
    - blind-watermark：盲水印工具
    - crc calculator：校验工具
    - f5：f5隐写工具
      * f5-steganography
      * lsb-steganography
      * steganography
    - foremost：分离工具
    - giftools：gif工具
    - gnuplot：
    - jphs：jpeg工具
    - mp3steno：mp3工具
    - namo gif animator：gif工具
    - openhashtab：hash工具
    - outguess：图片工具
    - pixrecovery：
    - pngcheck：png工具
    - qr_research：二维码工具
    - stegdetect：
    - steghide：捆绑工具
    - stegsolve：分离工具
    - tweakpng：png工具
    - wbstego：
    - ctf 密码学知识点总结
    - ctf 逆向知识点总结
    - ctf 隐写术知识点总结

**`[+] TrafficTools 流量工具:`**

    - burpsuite: 
      * burpsuite 2022.1.1汉化版（https://github.com/funkyoummp/burpsuitecn）
      * 集成插件：
        - vulners scanner
        - changeu
        - chunked coding converter
        - domain hunter
        - fake ip
        - hackbar
        - sqlmap4burp
        - turbo intruder
    - fiddler: 流量抓包工具（汉化版）
    - ftpservers: ftp开启工具  
    - hack firefox: firefox 49.0 （集成插件版）
    - ipchanger: ip代理工具  
    - phpstudy: 集成环境 
      * 集成thinkphp3.1.3 — 5.0.24全部版本
    - proxifier: 流量代理工具  
    - shadowsocks: socks代理工具 
    - torbrowser: 洋葱浏览器
    - wireshark: 流量抓包分析工具
    
**`下载链接：`**

链接：https://pan.xunlei.com/s/VN0C7m2p1mbLDPPu0j_UwRsVA1
提取码：ehpm

**`截图预览：`**

![image](https://raw.githubusercontent.com/makoto56/penetration-suite-toolkit/main/1.png)
![image](https://raw.githubusercontent.com/makoto56/penetration-suite-toolkit/main/2.png)
![image](https://raw.githubusercontent.com/makoto56/penetration-suite-toolkit/main/3.png)
![image](https://raw.githubusercontent.com/makoto56/penetration-suite-toolkit/main/4.png)
![image](https://raw.githubusercontent.com/makoto56/penetration-suite-toolkit/main/5.png)
![image](https://raw.githubusercontent.com/makoto56/penetration-suite-toolkit/main/6.png)
![image](https://raw.githubusercontent.com/makoto56/penetration-suite-toolkit/main/7.png)
![image](https://raw.githubusercontent.com/makoto56/penetration-suite-toolkit/main/8.png)

**`壁纸推荐：`**

![image](https://github.com/makoto56/penetration-suite-toolkit/blob/main/black_lock.png)
![image](https://github.com/makoto56/penetration-suite-toolkit/blob/main/black_main.png)
![image](https://github.com/makoto56/penetration-suite-toolkit/blob/main/blue_lock.png)
![image](https://github.com/makoto56/penetration-suite-toolkit/blob/main/blue_main.png)
![image](https://github.com/makoto56/penetration-suite-toolkit/blob/main/kali-windows-red.png)
![image](https://github.com/makoto56/penetration-suite-toolkit/blob/main/kali-windows-white.png)
