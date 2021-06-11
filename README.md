# mod-for-cs1.6

# 需求
由于中国人们计算机基础较差，加上国内资本垄断，导致游戏世界尤为混乱。导致cs1.6不止从何时开始竟然找不到带机器人版本以及可靠的联机版本。

# 论坛
点通论坛较为可靠

https://dt-club.net/forum-98-1.html

# Master Server
master server是用于配置服务器搜索

下载MasterServers.vdf放入\platform\config\中，也可以查找单个服务器，但是该网站太老了，很多地址比较旧。有些国外服务器虽然ping表面很低，实际上游戏里经常卡顿。

http://css.setti.info/masterserver/masterserver-instructions/

查找单个服务器

https://www.battlemetrics.com/servers/cs

# 推荐服务器

## 经典CS1.6休闲养老服[江苏电信]

右键connect可以使用正版steam的cs1.6连接此服务器，之后从历史记录中收藏至我的喜爱便可以了

或者非正版也可以在我的喜爱里面点击添加服务器手动添加地址114.225.36.230:27015或者cs2000.f3322.net:27015 

https://www.battlemetrics.com/servers/cs/9914663
## 华东经典cs1.6战斗服
42.192.209.200:27015

## 5eplay

5eplay的约战服务器

http://vs.5eplay.com/

# 绑定一键买枪
一键买枪一般有两种方法

一是在游戏中设置：

在游戏设置里面键盘选项卡（一般默认的功能键区，就是F1到F8都可以买武器套装）

但是对于正版游戏或者一些其他的版本中没有设置的选项，这就需要玩家们用到一键买枪的脚本了。下面是具体的操作方法：

打开游戏安装目录，用记事本打开cstrike文件夹里的config.cfg文件，在最底部加上exec userconfig.cfg，然后在cstrike文件夹里新建一个userconfig.cfg，再把以下参数黏贴进去保存即可。

学习版玩家直接复制下面参数进config.cfg文件即可。因为正版steam会保护config.cfg文件。

bind "F1" "fiveseven;Eltie;vesthelm;vest;secammo;hegren;flash;flash;sgren;defuser;secammo;"
Deagle套装

bind "F2" "p90;fiveseven;Eltie;vesthelm;vest;primammo;hegren;flash;flash;sgren;defuser;secammo;"
p90套装

bind "F3" "xm1014;fiveseven;Eltie;vesthelm;vest;primammo;hegren;flash;flash;sgren;defuser;secammo;"
xm1014套装

bind "F4" "famas;galil;fiveseven;Eltie;vesthelm;vest;primammo;hegren;flash;flash;sgren;defuser;secammo;"
Famas/Galil套装

bind "F5" "m4a1;ak47;fiveseven;Eltie;vesthelm;vest;primammo;hegren;flash;flash;sgren;defuser;secammo;"
M4/AK+Deagle套装

bind "F6" "aug;sg552;fiveseven;vesthelm;vest;primammo;hegren;flash;flash;sgrendefuser;secammo;"
AUG/Sg522套装

bind "F7" "awp;fiveseven;vesthelm;vest;secammo;buyammo1;hegren;flash;sgren;flash;sgren;defuser;secammo"
AWP套装

http://www.paopaoche.net/gonglue/41868.html

http://games.sina.com.cn/z/cs/2004-04-21/128140.shtml

# 被垃圾服务器篡改
根据修改文件查看什么被改了，试着改回来，或者重新覆盖安装。

https://tieba.baidu.com/p/3000815262?red_tag=3500915229

但实际上改了还是自动连接到那个垃圾服务器，很麻烦，所以还是花10块钱买个正版好一点。

把重要文件设置成只读或者仅管理员可以更改。

可以上点通论坛安装可靠的刷服务器补丁master server，同时过滤掉垃圾服务器。玩游戏的时候去一些可靠的服务器，不要去一些乱七八糟的服务器。

http://www.goqoq.com/cs16liumangserver.html

# 问题
似乎因为老版本的cs1.6无法进入新版本的cs1.6的服务器，加上太多垃圾服务器，所以推荐买个正版，然后再添加服务器比较方便。或者加入一些社区和讨论组能够搞到纯净的新版cs1.6。现在的游戏社区都被一些垃圾搞坏了，也是因为在中国游戏发展畸形的原因，导致大量人赚不到钱，才动了歪心思。

外国cs1.6版本无法连接到中国cs1.6服务器，很多网站提供的MasterServer不包括中国服务器。

#枪支名称对照表
CS:GO枪械基础绑定指令格式如下：

bind + 键位名称 + "buy 枪械名称" (输入时无需添加"+"号)

小键盘键位名称及对应键位表：

kp_slash (对应键位 "/")

kp_multiply (对应键位 "*")

kp_minus (对应键位 "-")

kp_home (对应键位 "7")

kp_uparrow (对应键位 "8")

kp_pgup (对应键位 "9")

kp_leftarrow (对应键位 "4")

kp_5 (对应键位 "5")

kp_rightarrow (对应键位 "6")

kp_end (对应键位 "1")

kp_downarrow (对应键位 "2")

kp_pgdn (对应键位 "3")

kp_ins (对应键位 "0")

kp_del (对应键位 ".")

kp_plus (对应键位 "+")

kp_enter (对应键位 "Enter")

CSGO枪械名称及对应指令大全(括号里为控制台所对应的枪械名称)

步枪：

Scout (ssg08)

Galil (galilar)

Famas (famas)

SG550 (sg550)

AUG (aug)

M4 (m4a1)

AK47 (ak47)

T专用步枪 (g3sg1)

CT专用步枪 (scar20)

AWP (awp)

冲锋枪：

Mac 10 (mac10)

UMP (ump45)

P90 (p90)

Bizon (bizon)

MP7 (mp7)

MP9 (mp9)

霰弹枪：

Auto Shotgun (xm1014)

Mag7 (mag7)

Sawed Off Shotgun (sawedoff)

Nova Shotgun (nova)

M249 (m249)

Negev (negev)

手枪：

228 Compact (p228)

Glock (glock)

Dual Elites (elite)

Five Seven (fiveseven)

Desert Eagle (deagle)

Tec9 (tec9)

HKP2000 (hkp2000)

P250 (p250)

手雷及装备：

Incendiary Grenade (incgrenade)

Flashbang (flashbang)

Smoke (smokegrenade)

HE Grenade (hegrenade)

Molotov (molotov)

Decoy (decoy)

Kevlar (kevlar)

Kevlar+Helmet (vesthelm)

Zeus x27 (taser)

Defuse Kit (defuser)

参考文献：https://www.te5.com/csgo/2016/120937.html
