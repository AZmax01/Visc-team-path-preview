# 整理CTF方向

此篇文章旨在介绍:

1.CTF前要具备的基本能力.

2.通过owasp top 10与相关题目的实践内容进行知识的针对性练习.

3.目前只收录了web,pwn,misc



一个基础路线博客:

https://blog.csdn.net/kailiaq_1/article/details/146195927



## Step1:基础

语言基础首推[菜鸟教程]([菜鸟教程 - 学的不仅是技术，更是梦想！](https://www.runoob.com/))和[w3schools]([w3schools 在线教程 - 免费开发设计教程网](https://www.w3ccoo.com/))

### --语言基础

### １.Python　

request、os、sys、pwntools、pip包管理器……

学习平台：菜鸟教程www.runoob.com

练习平台：[Python 练习、练习、挑战 – PYnative](https://pynative.com/python-exercises-with-solutions/)

github开源项目：[Security-Learning/PythonSec at main · H3rmesk1t/Security-Learning](https://github.com/H3rmesk1t/Security-Learning/tree/main/PythonSec)

涉及到的库、漏洞函数等必须清楚罗列，
相应的学习平台和练习平台必须要有，
其对应的CTF题目要很清楚，考点要很清晰，
以及WP的详细解题步骤都要核对。

[一文掌握CTF中Python全部考点_ctf python-CSDN博客](https://blog.csdn.net/qq_32277727/article/details/140620146)

### ２.PHP+apache

apache：日志分析：1.error.log 2.access.log（apache只需看懂这两个即可）

PHP：代码审计、反序列化、伪协议、语言特性（PHP相对简单）

学习平台：

菜鸟教程www.runoob.com

[PHP 教程](https://www.w3ccoo.com/php/)



### 3 .HTML+CSS+JS+MySQL

菜鸟教程:https://www.runoob.com/

### w3school:https://www.w3schools.com/



### --OS基础操作

Linux

Windows





## Step2:WP

主要做Owasp类型题的分析总结,抽离题型知识点,并总结语言所用到的<东西>



## Step3.语言漏洞对应练习专题



## Step4.Owasp Top 10类型练习专题

将WP的分析与总结的题总结到这里,以供练习

1.SQL注入

2.失效的身份认证

3.敏感信息泄露

4.XML外部实体漏洞

5.无效的访问控制

6.安全配置错误

7.跨站脚本攻击

8.不安全的反序列化漏洞

9.使用含有已知漏洞的组件

10.日志记录和监控不足导致的风险

详细见以下文章:

[OWASP Top 10：2021 年](https://owasp.org/Top10/)

[owasp top10 | 十大常见漏洞详解_owasp top 10 2024-CSDN博客](https://blog.csdn.net/m0_73826804/article/details/136226960)



## Step5.信息泄露

目录遍历

PHPINFO

网站备份压缩文件    #工具：御剑

.git泄露

.svn泄露     #工具：Seay-SVN [kost/dvcs-ripper: Rip web accessible (distributed) version control systems: SVN/GIT/HG...](https://github.com/kost/dvcs-ripper)

.hg泄露

.DS_Store泄露

.swp泄露

.bak泄露

web-INF/web.xml泄露

CVS泄露

Step6：web



## Step6:pwn

硬核知识---暂且没有思路

基础知识:

计算机组成原理 操作系统 程序运行原理 可执行文件结构 汇编语言 代码审计 系统内核调试 

驱动编写 二进制漏洞挖掘 静态分析

[Environment - CTF Wiki](https://ctf-wiki.org/pwn/linux/user-mode/environment/)



## Step7:Misc

[CTFHub](https://www.ctfhub.com/#/skilltree)

已知以下几种方式,并不详尽,后续补充

图片隐写  流量分析  压缩包隐写  编码相关  文档隐写  内存取证  音频隐写



## 注:CTF练习平台

作为题源,持续输出文章和题目

bugku:   https://ctf.bugku.com/

攻防世界： https://adworld.xctf.org.cn/

BUUCTF： https://buuoj.cn/

CTFhub： https://www.ctfhub.com/

看雪CTF：https://passport.kanxue.com/

CTFShow:  https://ctf.show/

麟阁:  https://www.venuskylin.com.cn/#/ctf

NSS:  https://www.nssctf.cn/index

CTF工具：

Fenjing：[[SSTI自动化工具\]Fenjing安装说明_fenjing ssti-CSDN博客](https://blog.csdn.net/m0_61155226/article/details/131671131)

