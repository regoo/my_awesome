- Burp Suite – web应用渗透测试的集成平台
- [EKFiddle](https://github.com/malwareinfosec/EKFiddle)
>A framework based on the Fiddler web debugger to study Exploit Kits, malvertising and malicious traffic in general.
- Cms-explorer – CMS Explorer设计用来寻找特定模块，插件，组件，主题等许多CMS相关的漏洞
- Dvcs-ripper – Rip web 入口 (分布式) 版本控制系统.
- Fimap – 发现，准备，审计，利用，甚至自动google LFI/RFI漏洞
- Joomscan – Joomla CMS 扫描器.
- Kadabra – 自动化 LFI 利用和扫描，用C++编写，有些外部模块是用python编写的.
- Kadimus – LFI 扫描和利用工具.
- Liffy – LFI 利用工具.
- Netsparker – Web 应用安全扫描.
- Nikto2 – Web 应用漏洞扫描工具.
- NoSQLMap – 自动 Mongo 数据库和 NoSQL web 应用漏洞利用工具.
- OWASP Xenotix – XSS 利用框架是一个 跨站脚本攻击 (XSS) 漏洞检测和利用框架.
- Paros – 基于JAVA的 HTTP/HTTPS 代理，用于评估web应用漏洞
- Ratproxy –半自动化的 web 应用安全审计工具, 能够精确敏感的检测并标注潜在的问题。
- Scout2 – AWS 环境的安全审计工具.
- Skipfish – 一个主动的 web 应用安全探测工具。 它提供一个交互式的目标站点的站点地图，通过递归爬取目标网站.
- SQLMap – 自动化 SQL 注入和数据库接管工具.
- SQLNinja – SQL Server 注入和接管工具.
- TPLMap – 自动化服务端模板注入检测利用工具
- Yasuo – 一个 ruby 脚本，扫描第三方web应用的漏洞并利用
- W3af – Web 应用攻击和审计框架.
- Wapiti – Web 应用漏洞扫描.
- Weevely3 – 武器化 web shell.
- WPScan – WPScan是一个黑盒 WordPress 漏洞扫描工具.
- WPSploit – 使用Metasploit攻击 Wordpress.
- WS-Attacker – web服务渗透测试的模块化框架
- Zed Attack Proxy (ZAP) – OWASP ZAP 核心项目.
- imaginaryC2 是一款python工具，可帮助安全研究人员分析恶意软件（网络）行为。Imaginary C2上托管了一个HTTP服务器，用于捕获选定域/IP的HTTP请求。此外，该工具还可用于重放捕获的C&C响应/payloads，使这个过程变得更加方便快捷。

## fuzz工具

- Fusil – 用于编写模糊测试程序的python库。它能够在预定义的环境中启动进程（限定内存，环境变量，重定向输出流，等等），开启网络客户端和服务器，以及创建损坏的文件.
- Fuzzbox – 多解码媒体模糊测试工具.
- Netzob – Netzob 是一个开源逆向工程工具,流量生成，通信协议模糊测试
- Python-AFL – 纯python写的American fuzzy lop 子服务工具.
- Sulley – 模糊测试开发和模糊测试框架，包含多个可扩展的组件
- TAOF – The Art of Fuzzing, 包含 ProxyFuzz, 中间人网络模糊测试.
- Windows IPC Fuzzing Tools – 利用windows进程通信机制的一系列攻击工具.
- Zulu – 一个快速原型模糊测试工具，通常用于与客户端交互的时间线上子域名枚举
https://github.com/lijiejie/subDomainsBrute (经典的子域名爆破枚举脚本)
https://github.com/ring04h/wydomain (子域名字典穷举)
https://github.com/le4f/dnsmaper (子域名枚举与地图标记)
https://github.com/0xbug/orangescan (在线子域名信息收集工具)
https://github.com/TheRook/subbrute （根据DNS记录查询子域名)
https://github.com/We5ter/GSDF (基于谷歌SSL透明证书的子域名查询脚本)
https://github.com/mandatoryprogrammer/cloudflare_enum （使用CloudFlare进行子域名枚举的脚本）
https://github.com/18F/domain-scan (A domain scanner）
https://github.com/guelfoweb/knock (Knock Subdomain Scan)
https://github.com/Evi1CLAY/CoolPool/tree/master/Python/DomainSeeker （多方式收集目标子域名信息）
https://github.com/code-scan/BroDomain (兄弟域名查询）
https://github.com/chuhades/dnsbrute (基于dns查询的子域名枚举)
https://github.com/ivanfratric/winafl
https://github.com/attekett/NodeFuzz
https://github.com/google/oss-fuzz
http://blog.topsec.com.cn/ad_lab/alphafuzzer/
http://llvm.org/docs/LibFuzzer.html

## 扫描工具
### web应用扫描器
http://github.com/Arachni/arachni   （web应用安全扫描器框架 http://www.arachni-scanner.com）

### 数据库扫描、注入工具
https://github.com/sqlmapproject/sqlmap （注入工具之王sqlmap）
https://github.com/0xbug/SQLiScanner (一款基于SQLMAP和Charles的被动SQL注入漏洞扫描工具)
https://github.com/stamparm/DSSS (99行代码实现的sql注入漏洞扫描器)
https://github.com/youngyangyang04/NoSQLAttack (一款针对mongoDB的攻击工具)
https://github.com/Neohapsis/bbqsql （SQL盲注利用框架）
https://github.com/NetSPI/PowerUpSQL （攻击SQLSERVER的Powershell脚本框架）
https://github.com/WhitewidowScanner/whitewidow (又一款数据库扫描器)
https://github.com/stampery/mongoaudit (MongoDB审计及渗透工具）
https://github.com/commixproject/commix （注入点命令执行利用工具）

### 弱口令或信息泄漏扫描
https://github.com/lijiejie/htpwdScan (一个简单的HTTP暴力破解、撞库攻击脚本)
https://github.com/lijiejie/BBScan (一个迷你的信息泄漏批量扫描脚本)
https://github.com/lijiejie/GitHack (.git文件夹泄漏利用工具)
https://github.com/LoRexxar/BScanner  （基于字典的目录扫描小工具）
https://github.com/she11c0der/fenghuangscanner_v3  (各种端口及弱口令检测，作者wilson9x1，原地址失效)
https://github.com/ysrc/F-Scrack （对各类服务进行弱口令检测的脚本)
https://github.com/Mebus/cupp （根据用户习惯生成弱口令探测字典脚本）
https://github.com/RicterZ/genpAss （中国特色的弱口令生成器）
https://github.com/netxfly/crack_ssh （go写的协程版的ssh\redis\mongodb弱口令破解工具）
https://github.com/n0tr00t/Sreg (通过输入email、phone、username的返回用户注册的所有互联网护照信息)
https://github.com/repoog/GitPrey (GitHub敏感信息扫描工具)
https://github.com/dxa4481/truffleHog (GitHub敏感信息扫描工具,包括检测commit等)
https://github.com/LandGrey/pydictor (暴力破解字典建立工具)
https://github.com/GDSSecurity/xxe-recursive-download  （xxe漏洞递归下载工具）
https://buer.haus/xxegen/  （xxe在线生成利用工具）

### 物联网设备扫描
https://github.com/rapid7/IoTSeeker （物联网设备默认密码扫描检测工具)
https://github.com/shodan-labs/iotdb (使用nmap扫描IoT设备)
https://github.com/jh00nbr/Routerhunter-2.0 （路由器漏洞扫描利用)
https://github.com/reverse-shell/routersploit   （路由器漏洞利用框架）
https://github.com/scu-igroup/telnet-scanner (telnet服务密码撞库)
https://github.com/RUB-NDS/PRET                 （打印机攻击框架）

### XSS扫描
https://github.com/shawarkhanethicalhacker/BruteXSS （Cross-Site Scripting Bruteforcer）
https://github.com/1N3/XSSTracer (A small python script to check for Cross-Site Tracing)
https://github.com/0x584A/fuzzXssPHP (PHP版本的反射型xss扫描)
https://github.com/chuhades/xss_scan (批量扫描xss的python脚本）
https://github.com/BlackHole1/autoFindXssAndCsrf (自动化检测页面是否存在XSS和CSRF漏洞的浏览器插件）

### 企业网络自检
https://github.com/sowish/LNScan （详细的内部网络信息扫描器）
https://github.com/SkyLined/LocalNetworkScanner (javascript实现的本地网络扫描器)
https://github.com/ysrc/xunfeng (网络资产识别引擎，漏洞检测引擎）
https://github.com/laramies/theHarvester （企业被搜索引擎收录敏感资产信息监控脚本：员工邮箱、子域名、Hosts）
https://github.com/x0day/Multisearch-v2  (搜索引擎聚合搜索，可用于发现企业被搜索引擎收录的敏感资产信息）

### webshell检测以及病毒分析工具
https://github.com/We5ter/Scanners-Box/tree/master/webshell/ （简单的php后门检测工具以及webshell样本库）
https://github.com/ym2011/ScanBackdoor （Webshell扫描工具）
https://github.com/yassineaddi/BackdoorMan （PHP后门扫描）
https://github.com/he1m4n6a/findWebshell （又一款webshell检测工具)
https://github.com/Tencent/HaboMalHunter （哈勃分析系统，linux系统病毒分析及安全检测）
https://github.com/PlagueScanner/PlagueScanner (使用python实现的集成ClamAV、ESET、Bitdefender的反病毒引擎)
https://github.com/nbs-system/php-malware-finder (一款高效率PHP-webshell扫描工具)
https://github.com/emposha/PHP-Shell-Detector/ (测试效率高达99%的webshell检测工具)

### 内网安全渗透测试工具集
https://github.com/0xwindows/VulScritp               （企业内网渗透脚本，包括banner扫描、端口扫描；各种通用漏洞利用等）
https://github.com/lcatro/network_backdoor_scanner （基于网络流量的内网探测框架）
https://github.com/fdiskyou/hunter            （调用 Windows API 枚举用户登录信息）
https://github.com/BlackHole1/WebRtcXSS （自动化利用XSS入侵内网）
https://github.com/AlessandroZ/LaZagne    （本机密码查看提取工具）
https://github.com/huntergregal/mimipenguin （linux密码抓取神器）

### 端口扫描、指纹识别以及中间件扫描
https://nmap.org/download.html        (Nmap端口扫描器之王,https://svn.nmap.org/)
https://github.com/ring04h/wyportmap  (目标端口扫描+系统服务指纹识别)
https://github.com/ring04h/weakfilescan (动态多线程敏感信息泄露检测工具)
https://github.com/EnableSecurity/wafw00f (WAF产品指纹识别)
https://github.com/rbsec/sslscan （ssl类型识别)
https://github.com/urbanadventurer/whatweb (web指纹识别)
https://github.com/tanjiti/FingerPrint (web应用指纹识别)
BlindElephant – Web 应用指纹
WhatWeb – 网站指纹.
https://github.com/nanshihui/Scan-T （网络爬虫式指纹识别)
https://github.com/OffensivePython/Nscan (a fast Network scanner inspired by Masscan and Zmap)
https://github.com/ywolf/F-NAScan (网络资产信息扫描, ICMP存活探测,端口扫描，端口指纹服务识别）
https://github.com/ywolf/F-MiddlewareScan （中间件扫描）
https://github.com/maurosoria/dirsearch (Web path scanner)
https://github.com/x0day/bannerscan （C段Banner与路径扫描）
https://github.com/RASSec/RASscan (端口服务扫描)
https://github.com/3xp10it/bypass_waf （waf自动暴破）
https://github.com/3xp10it/xcdn (尝试找出cdn背后的真实ip)
https://github.com/Xyntax/BingC （基于Bing搜索引擎的C段/旁站查询，多线程，支持API）
https://github.com/Xyntax/DirBrute （多线程WEB目录爆破工具）
https://github.com/zer0h/httpscan （一个爬虫式的网段Web主机发现小工具）
https://github.com/lietdai/doom （thorn上实现的分布式任务分发的ip端口漏洞扫描器）
https://github.com/chichou/grab.js (类似 zgrab 的快速 TCP 指纹抓取解析工具，支持更多协议)
https://github.com/Nitr4x/whichCDN (CDN识别、检测）
https://github.com/secfree/bcrpscan (基于爬虫的web路径扫描器)

### 针对性漏洞测试工具
https://github.com/brianwrf/hackUtils （java反序列化利用工具集）
https://github.com/frohoff/ysoserial （ java反序列化利用工具）
https://github.com/blackye/Jenkins (Jenkins漏洞探测、用户抓取爆破)
https://github.com/code-scan/dzscan (discuz漏洞扫描)
https://github.com/chuhades/CMS-Exploit-Framework (CMS攻击框架)
https://github.com/lijiejie/IIS_shortname_Scanner (IIS短文件名漏洞扫描)
https://github.com/riusksk/FlashScanner (flashxss扫描)
https://github.com/coffeehb/SSTIF （服务器端模板注入漏洞的半自动化工具）
https://github.com/epinna/tplmap (服务器端模板注入漏洞检测与利用工具)
https://github.com/cr0hn/dockerscan (docker扫描工具)
https://github.com/GoSecure/break-fast-serial （借助DNS解析来检测Java反序列化漏洞工具）
https://github.com/dirtycow/dirtycow.github.io （脏牛提权漏洞exp）

### 代码静态扫描、代码运行栈跟踪
https://github.com/exakat/php-static-analysis-tools （php静态扫描工具集）
https://github.com/wufeifei/cobra (白盒代码安全审计系统)
https://github.com/OneSourceCat/phpvulhunter (静态php代码审计)
https://github.com/Qihoo360/phptrace (跟踪、分析PHP运行情况的工具）
https://github.com/ajinabraham/NodeJsScan (NodeJS应用代码审计）
https://github.com/pwnsdx/BadCode   （PHP代码审计）
https://github.com/thesp0nge/dawnscanner （ruby源码审计）
https://github.com/presidentbeef/brakeman  （Ruby on Rails应用程序的安全漏洞）
https://github.com/ajinabraham/Mobile-Security-Framework-MobSF/    （app黑盒审计）
https://github.com/alibaba/iOSSecAudit   （iOS安全审计）

### 模块化扫描、综合扫描器
https://github.com/az0ne/AZScanner (自动漏洞扫描器，子域名爆破，端口扫描，目录爆破，常用框架漏洞检测)
https://github.com/blackye/lalascan (分布式web漏洞扫描框架，集合owasp top10漏洞扫描和边界资产发现能力)
https://github.com/blackye/BkScanner (BkScanner 分布式、插件化web漏洞扫描器)
https://github.com/ysrc/GourdScanV2 （被动式漏洞扫描)
https://github.com/alpha1e0/pentestdb (WEB渗透测试数据库)
https://github.com/netxfly/passive_scan (基于http代理的web漏洞扫描器)
https://github.com/1N3/Sn1per (自动化扫描器，包括中间件扫描以及设备指纹识别)
https://github.com/RASSec/pentestEr_Fully-automatic-scanner （定向全自动化渗透测试工具）
https://github.com/3xp10it/3xp10it （自动化渗透测试框架)
https://github.com/Lcys/lcyscan (扫描效果未验证）
https://github.com/Xyntax/POC-T （渗透测试插件化并发框架）
https://github.com/v3n0m-Scanner/V3n0M-Scanner （Scanner in Python3.5 for SQLi/XSS/LFI/RFI and other Vulns）
https://github.com/Skycrab/leakScan （web端的在线漏洞扫描）
https://github.com/zhangzhenfeng/AnyScan (开发中…)

Database firewall：
https://nim4.github.io/DBShield/

### waf开源及规则：
https://github.com/xsec-lab/x-waf
https://github.com/loveshell/ngx_lua_waf
https://github.com/SpiderLabs/owasp-modsecurity-crs/tree/master/base_rules