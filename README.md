# wwnb patch

## 介绍
用于尤里mod wwnb的问题修复或参数优化。

针式平衡，只准强化不准削弱。

## 补丁日志

2019.3.31 修改妈妈船价格说明文件还有初始部队的bug,降低喷火坦克价格，增强超时空转换，增强喷火坦克













--------------

# MOD说明

## Yuri's Revenge Mod - World Wide Network Base

### 特色：注重超武和远程打击

### **公素来源链接及mod下载在最后**


## 项目原地址：

https://gitee.com/grdaimap/wwnb

> 注意：开源允许修改，当然只改改参数的可不能算作新mod，新单位都是公共素材。

-----------
## 介绍
>危险等级：S(极度危险) A(危险) B(重视) C(一般) D(忽视)
## 超武列表


### 公有超武

超武名称|危险等级|作用|持续|冷却|花费|需要电力|影响范围|伤害
---|:--|:--|:--|:--|:--|:--|:--|:--:
力场护盾|A|加强版的力场护盾，断电时间1.1|0.8|4|-|是|6|-
心灵探测|D|原版的心灵探测在这个全球化卫星信息作战的mod没有用，直接赠送|-|4|-|否|8|-|
### 萌军阵营

> 拥有所有原版尤里盟军的装备，比如黑鹰战机，狙击手，巨炮等等。


超武名称|危险等级|作用|持续|冷却|花费|需要电力|影响范围|伤害
---|:--|:--|:--|:--|:--|:--|:--|:--:
EMP镭射|A|瘫痪敌人的建筑或载具,停止超武计时和各种动作|3.3|4|600|是|7|100
空降部队|A(B)|在任意地点空降一个排兵力，默认8大兵，4灰熊，2光棱，对油里威胁降低|-|5|1000|否|-|-
光学隐身|A(B)|萌军研究铁幕发明的超武，使单位隐身，对油里威胁降低|2|4|800|否|6|-
超时空传送|A|加强版的超时空，可运步兵|-|6|-|是|6|-
闪电风暴|S|加强版的闪电风暴|0.5|10|-|是|>15|1000(?)~24000(?)
时间停止(全域EMP)|S|停止全图时间|5|6.5|-|是|∞|-



### 酥军阵营

> 拥有所有原版尤里苏军的装备，比如恐怖分子，自爆卡车，磁能坦克等等。

超武名称|危险等级|作用|持续|冷却|花费|需要电力|影响范围|伤害
---|:--|:--|:--|:--|:--|:--|:--|:--:
地火辐射|A(B)|在2*2范围内引起火灾，烧毁除建造厂超武船厂之外的建筑，对玩家影响较轻|1|6|600|是|3|<9000
超级前线战斗碉堡|A|投放一个满员的升级版战斗碉堡|-|5.5|800|否|-|-
核平侦查机|A|装有核电池的侦察机，可以不停在敌方上空飞行|-|12|200|否|0~9|0~480
铁幕保护|S|升级版铁幕|1.1|6|-|是|5|-
核弹打击|S|升级版核弹|-|10|-|是|12|900~10800
休伯利安支援|S|召唤休伯利安号对敌方基地进行毁灭性打击|-|8|-|是|30|-




### 油里阵营

> 拥有所有原版所有尤里的装备，比如……等等。

超武名称|危险等级|作用|持续|冷却|花费|需要电力|影响范围|伤害
---|:--|:--|:--|:--|:--|:--|:--|:--:
油里前哨|A|投放心控塔和坦克碉堡|-|6|1100|否|-|-
远距心控|B|远距离控制敌方心智单位，注意是弱控制|-|7|800|是|3|10
超声波反隐形|D(B)|对抗萌军的隐身装甲和潜水单位，对萌军构成威胁|0.9|3|500|否|8|80
基因突变|A|基因突变，把士兵变成狂兽人|-|5|-|是|5|-
心灵支配|S|升级版心灵支配|-|10|-|是|6|1000~6000(?)
空降仓|B|在二阶科技下不断往复制中心处运送士兵|-|1.5|300|否|-|-
太阳轰炸|S|对敌方基地进行毁灭性打击|0.3|5|-|是|-|600~60000（？）










-----------
## 新建筑列表


建筑名称|所属|作用|建造前提|花费
---|:--|:--|:--|:--
因果防御塔|萌军|给自己加buff对方进攻部队debuff|萌军实验室和战车工厂|3000
钢铁防御塔|酥军|给自己的防御单位加铁幕|核弹井，工业工厂，核子反应堆|3000
生化防御塔|油里|毒气打击侵略者，维修治疗友军|克隆工厂，基因突变器,部队回收厂|3000
平行时空科技实验室|萌军|解锁多个萌军新单位和最终超武|因果防御塔|2000
改进科技实验室|酥军|解锁多个酥军新单位和最终超武|钢铁防御塔|2000
生化科技研究所|油里|解锁多个油里新单位和最终超武|生化防御塔|2000



## 新单位列表

### 萌军阵营

单位名称|危险等级|作用|科技等级T
---|:--|:--|:--
裂缝支援坦克|B|部署成裂缝发生器，抑制范围最大20抵御除了终极超武外其他的超武攻击，非部署状态可以超时空移动到地图各处，主武器为治疗炮，可以迅速修好载具建筑|5
千年隼运兵船|A|主武器时空抹除炮，初始携带基地车和一些坦克，静止时隐形|6
新星天气舰|S|主武器小型雷暴云，载员武器为黑风暴|6
伊卡洛斯离子炮|A|主武器离子炮，载员武器为ifv飞弹|6
黑鸟音速战机|A|速度很快血量弹药提升的战斗机|5
神盾局激光空舰|A|携带斯塔克量产无人机科技，主武器为激光无人机发射，载员武器为火箭兵激光|5


### 酥军阵营

单位名称|危险等级|作用|科技等级T
---|:--|:--|:--
核磁潜艇|S|主武器为远距核弹，副武器是磁电攻击|5
铁幕波能|S|盖特逻辑，一阶段是精英天启武器，二阶段是铁幕磁雨，三阶段是波能毁灭炮|6
喷火坦克|A|武器系统为火焰粒子系统，具有穿透伤害|5
基洛夫空舰|A|在原来的基洛夫外面包了外壳，载员有天启坦克，主武器是发射磁电小飞机|5
点三支援直升机|A|当敌军载具血量不足70%可以击杀驾驶员使载具中立，可以用工程师占领载具，自带4个工程师和1个鲍里斯|6
原谅高空气球|S|主武器是弱化的埃菲尔铁塔，部署武器是范围20的辐射区|5
休伯利安号|S|？？？？？？反正很强就是了？？？？？|7





### 油里阵营

单位名称|危险等级|作用|科技等级T
---|:--|:--|:--
星灵水晶兵|A|最强步兵，部署前武器是激光枪，部署后武器是治疗枪，可以偷敌人载具|6
突突突三轮|A|携带尤里X磁暴步兵防空步兵的载具，主武器是发射悬浮毒气无人机，其移动方式鬼畜|5
星灵航母|A|？？？总之能发射子机，伤害不小？？？|6
星灵虚空舰|A|？？？总之激光炮威力不错？？？|6
星灵妈妈船|S|？？？激光炮和大炸弹？？|7
复制中心冰激凌车|A|冰激凌车的主武器是EMP治疗炮，可以治疗被EMP的单位，部署成复制中心且在二阶科技下会有不断的步兵增援|6


















## 彩蛋（其他修改）列表

单位名称|修改内容
---|:--
V3火箭车|射程无限远
盟军发电厂|产电400
苏军发电厂|产电200
尤里发电厂|产电250














----------------------

## 更新日志
时间|内容
---|:--:
19.3.9|完成6个小超武
19.3.11|添加3个超武，完善name，v0.6
19.3.16|添加6个二阶建筑，真的太麻烦了，v1.2，或者说v2-0.2
19.3.18|防御塔做好了
19.3.30|完工……剩下就是调AI了

-----------------------------
## 素材来源

- 百度搜索，图标，载入图

[中dwl002反隐形雷达震撼问世 f-22无处躲藏](https://image.baidu.com/search/redirect?tn=redirect&word=j&juid=84EAC3&sign=ckkeegaozc&url=http%3A%2F%2Fnews.k618.cn%2Fjs_37057%2F201410%2Ft20141008_5681513.html&objurl=https%3A%2F%2Ftimgsa.baidu.com%2Ftimg%3Fimage%26quality%3D80%26size%3Db9999_10000%26sec%3D1552241040490%26di%3Dc709fb43ce8c478f28d3344a6ab6b125%26imgtype%3D0%26src%3Dhttp%253A%252F%252Fnews.k618.cn%252Fjs_37057%252F201410%252FW020141008520233005638.jpg)

[哈利波特的"隐身斗篷"成为现实?](http://blog.sina.com.cn/s/blog_6ac62a8d0102uz6v.html)

[EA希望《星球大战：前线》挽回流失的老玩家](http://news.178.com/201511/240518445725.html)

[【少女前线手书】416生气了吗](https://www.bilibili.com/tag/73457/?pagetype=tagpage)

[[转载]【毛泽东书法】毛泽东为《人民前线》题写报头](https://image.baidu.com/search/redirect?tn=redirect&word=j&juid=FA517E&sign=ckkeegceig&url=http%3A%2F%2Fblog.sina.com.cn%2Fs%2Fblog_4a85d2160101guct.html&objurl=https%3A%2F%2Ftimgsa.baidu.com%2Ftimg%3Fimage%26quality%3D80%26size%3Db9999_10000%26sec%3D1552241322306%26di%3D0efebd6b802996c7aa14103baa42bee6%26imgtype%3D0%26src%3Dhttp%253A%252F%252Fs11.sinaimg.cn%252Fmw690%252F001p1ezWgy6DVUulNhgea%2526690)

[胜利纪念碑](https://image.baidu.com/search/redirect?tn=redirect&word=j&juid=D9CD6A&sign=ckkeegcoew&url=http%3A%2F%2Ftouch.go.qunar.com%2Fpoi%2F4454702%3Ffrom%3Dzaker1448665234CHK146779570714492087481900&objurl=https%3A%2F%2Ftimgsa.baidu.com%2Ftimg%3Fimage%26quality%3D80%26size%3Db9999_10000%26sec%3D1552242007506%26di%3Da4a2fda76d59470e108dd5757947d28d%26imgtype%3D0%26src%3Dhttp%253A%252F%252Fimg1.qunarzz.com%252Ftravel%252Fd2%252F1608%252F58%252F39bf1c68774d81b5.png_r_640x490x70_edaa5292.png)

[红警标志](https://image.baidu.com/search/index?tn=baiduimage&ipn=r&ct=201326592&cl=2&lm=-1&st=-1&fm=result&fr=&sf=1&fmq=1552302486777_R&pv=&ic=&nc=1&z=&hd=&latest=&copyright=&se=1&showtab=0&fb=0&width=&height=&face=0&istype=2&ie=utf-8&word=%E7%BA%A2%E8%AD%A6)

[星际穿越](https://image.baidu.com/search/detail?ct=503316480&z=0&ipn=d&word=%E6%97%B6%E9%97%B4%E9%9D%99%E6%AD%A2&step_word=&hs=0&pn=19&spn=0&di=152069205200&pi=0&rn=1&tn=baiduimagedetail&is=0%2C0&istype=0&ie=utf-8&oe=utf-8&in=&cl=2&lm=-1&st=undefined&cs=2522624134%2C4113676390&os=101227984%2C4076553516&simid=0%2C0&adpicid=0&lpn=0&ln=1894&fr=&fmq=1553853050708_R&fm=&ic=undefined&s=undefined&hd=undefined&latest=undefined&copyright=undefined&se=&sme=&tab=0&width=undefined&height=undefined&face=undefined&ist=&jit=&cg=&bdtype=0&oriquery=&objurl=http%3A%2F%2Fpic4.zhimg.com%2Fv2-f37df216ea57cca50cd44c8e3837cc37_r.jpg&fromurl=ippr_z2C%24qAzdH3FAzdH3Fooo_z%26e3Bziti7_z%26e3Bv54AzdH3Fq7jfpt5gAzdH3Fdbbcln8n9AzdH3Fwgfoj6AzdH3F9md9a99n0&gsm=0&rpstart=0&rpnum=0&islist=&querylist=&force=undefined)

[太阳](https://image.baidu.com/search/detail?ct=503316480&z=0&ipn=d&word=%E5%A4%AA%E9%98%B3%E8%BD%B0%E7%82%B8&step_word=&hs=0&pn=0&spn=0&di=45792787590&pi=0&rn=1&tn=baiduimagedetail&is=0%2C0&istype=2&ie=utf-8&oe=utf-8&in=&cl=2&lm=-1&st=-1&cs=4027764449%2C1286096386&os=578222444%2C938337274&simid=3451672972%2C367640755&adpicid=0&lpn=0&ln=1227&fr=&fmq=1553853331650_R&fm=detail&ic=undefined&s=undefined&hd=undefined&latest=undefined&copyright=undefined&se=&sme=&tab=0&width=undefined&height=undefined&face=undefined&ist=&jit=&cg=&bdtype=0&oriquery=&objurl=http%3A%2F%2Fimg1.gtimg.com%2Ftech%2Fpics%2Fhv1%2F117%2F88%2F2043%2F132868632.jpg&fromurl=ippr_z2C%24qAzdH3FAzdH3Fpjvi_z%26e3Bqq_z%26e3Bv54AzdH3FwAzdH3Fda8mandbAzdH3Fad9d0l_z%26e3Bip4&gsm=0&rpstart=0&rpnum=0&islist=&querylist=&force=undefined)

[空降图片](https://image.baidu.com/search/detail?ct=503316480&z=0&ipn=d&word=%E7%A9%BA%E9%99%8D&step_word=&hs=0&pn=1&spn=0&di=201599976600&pi=0&rn=1&tn=baiduimagedetail&is=0%2C0&istype=2&ie=utf-8&oe=utf-8&in=&cl=2&lm=-1&st=-1&cs=3792549033%2C1228628951&os=356205%2C2321211044&simid=3447040075%2C260882393&adpicid=0&lpn=0&ln=1785&fr=&fmq=1553853441407_R&fm=&ic=undefined&s=undefined&hd=undefined&latest=undefined&copyright=undefined&se=&sme=&tab=0&width=undefined&height=undefined&face=undefined&ist=&jit=&cg=&bdtype=0&oriquery=&objurl=http%3A%2F%2Fimg.weixinyidu.com%2F160127%2Fc93ab492.jpg&fromurl=ippr_z2C%24qAzdH3FAzdH3Fooo_z%26e3Bojtxtgyt17_z%26e3Bv54AzdH3Fg_dbla9ca&gsm=0&rpstart=0&rpnum=0&islist=&querylist=&force=undefined)

- 启动图，星际迷航发现号

[【星际迷航ol】联邦星舰发现号 燃向剪辑](https://image.baidu.com/search/redirect?tn=redirect&word=j&juid=C00EF4&sign=ckkegaegka&url=http%3A%2F%2Fwww.bilibili.com%2Fvideo%2Fav19565341%2F%3FredirectFrom%3Dh5&objurl=https%3A%2F%2Ftimgsa.baidu.com%2Ftimg%3Fimage%26quality%3D80%26size%3Db9999_10000%26sec%3D1552312429516%26di%3Da36d6c39867dfb6af849b352d4487e86%26imgtype%3D0%26src%3Dhttp%253A%252F%252Fi1.hdslb.com%252Fbfs%252Farchive%252F34873a5ea84af8fd56d87b9b6c34e511fd2a9937.png)



- 新增单位

[因果防御塔 @ Atomic_Noodles ](https://ppmforums.com/viewtopic.php?t=43903)

[钢铁防御塔 @ whenro](http://bbs.ra2diy.com/forum.php?mod=viewthread&tid=12811&highlight=%E9%98%B2%E5%BE%A1%E5%A1%94)

[生化反应塔 @ DonutArnold ](https://ppmforums.com/viewtopic.php?t=43424)

[萌军二阶实验室-风离子炮 @ 膜术师协会](http://bbs.ra2diy.com/forum.php?mod=viewthread&tid=15978&highlight=%E9%A3%8E%E7%A6%BB%E5%AD%90%E7%82%AE)

[酥军二阶实验室-苏联交流中心 @ OverWatch ](https://ppmforums.com/viewtopic.php?t=44745)

[油里二阶实验室-油里生化工厂 @ OverWatch ](https://ppmforums.com/viewtopic.php?t=44937)


[星灵妈妈船 @ 联邦星舰驱逐](https://tieba.baidu.com/p/6002340522?pid=123581443225&cid=0&red_tag=1524278939#123581443225)

[星灵航母舰队 @ 联邦星舰驱逐](https://tieba.baidu.com/p/6007228571?pid=123657517971&cid=0&red_tag=1371914952#123657517971)

[虚空辉光舰 @ 联邦星舰驱逐](https://tieba.baidu.com/p/6003647679?pid=123599658044&cid=0&red_tag=1401985628#123599658044)

[休得利安号 @ 联邦星舰驱逐](https://tieba.baidu.com/p/5994345185?pid=123465132296&cid=0&red_tag=1543667104#123465132296)

> 特殊说明：https://tieba.baidu.com/p/6083988423 作者对盗素材者忍无可忍，停止一切素材分享。使用录制必须“声明一点，尊重本人成果，尤其是这种开火音效语音，特效都调好的这种作品，当然其它的也不是就不用尊重了，毕竟我牺牲了我自己的时间做东西给大家玩，而我只希望你们尊重我的成果，另外使用并录制视频或者其它方面或者转载请标明作者”

[伊卡洛斯离子炮 @ daTS](https://ppmforums.com/viewtopic.php?t=13509)

[激光无人机 @ Muldrake ](https://ppmforums.com/viewtopic.php?t=8582)

[千年隼运兵船 @ OverWatch ](https://ppmforums.com/viewtopic.php?t=42193)

[裂缝超时空支援坦克 @ OverWatch](https://ppmforums.com/viewtopic.php?t=42800)

[酥军的磁力小飞机 @ Quiet ](https://ppmforums.com/viewtopic.php?t=38695)

[突突突-三轮 @ cxtian39](https://ppmforums.com/viewtopic.php?t=43985)

[毒气悬浮机 @ Agent Z ](https://ppmforums.com/viewtopic.php?t=40667)
> 特殊说明：Use only when credited. Made by Agent Z.



[铁幕波能 @ GoblinKnight](https://ppmforums.com/viewtopic.php?t=43265)

[很多素材 @ Anderwin 整理](https://ppmforums.com/viewtopic.php?t=39291)

[泰伯利亚素材包，使用了喷火小坦克 @ IVI ](https://ppmforums.com/viewtopic.php?t=12822&tdsourcetag=s_pctim_aiomsg)


[原谅高空气球 @ Shepherd Moons ](https://ppmforums.com/viewtopic.php?t=40131)

[支援直升机 @ Stingerr ](http://www.ppmsite.com/forum/viewtopic.php?t=12096)

[黑鸟音速战机 @ EricJP65 ](https://ppmforums.com/viewtopic.php?t=14300)

[复制中心冰激凌车 @ OverWatch ](https://ppmforums.com/viewtopic.php?t=45514)

[核磁潜艇 @ daTS Mr. Moosey](https://ppmforums.com/viewtopic.php?t=14006)

[基洛夫空舰 @ Arikado ](https://ppmforums.com/viewtopic.php?t=14227)

[神盾局 @ 搞基直接找我](http://bbs.ra2diy.com/forum.php?mod=viewthread&tid=14470&highlight=%E7%A5%9E%E7%9B%BE%E5%B1%80)

[新星天气舰 @ Daz ](https://ppmforums.com/viewtopic.php?t=14379)

> 特殊说明：Battlestar NovaBy DazThis is a Colonial Battlestar as seen in Battlestar Galactica (1978), with textures from the Battlestar.Galactica in Battlestar Galactica (200X).The plans I worked from were entitled Battlestar Nova, which isn't one of the original 12 Battlestars but looks identical to the original 12.I haven't put a name plate on the hanger pods so it can pass as the Galactica, Atlantia, Pegasus, etc.

> Credit Daz for use please.


- 动画

[龙卷风 @ 2864048202](http://bbs.ra2diy.com/forum.php?mod=viewthread&tid=14550&highlight=%E9%BE%99%E5%8D%B7%E9%A3%8E)

[离子炮动画 @ 双杀步枪](http://bbs.ra2diy.com/forum.php?mod=viewthread&tid=14724&highlight=%E7%A6%BB%E5%AD%90%E7%82%AE)

[离子炮动画2 @ 膜术师协会](http://bbs.ra2diy.com/forum.php?mod=viewthread&tid=15977&highlight=%E7%A6%BB%E5%AD%90%E7%82%AE)

[护盾动画 @ 紫色放逐](http://bbs.ra2diy.com/forum.php?mod=viewthread&tid=11658&highlight=%E6%8A%A4%E7%9B%BE)

[力场护盾2 @ kenosis ](https://ppmforums.com/viewtopic.php?t=33068)

[火焰火灾 @ ChronoBomb](http://bbs.ra2diy.com/forum.php?mod=viewthread&tid=10742&highlight=%E7%81%AB%E7%84%B0)


[火焰喷射武器代码 @ SDFGH](http://bbs.ra2diy.com/forum.php?mod=viewthread&tid=5060&highlight=%E7%81%AB%E7%84%B0)


[黑风暴原理-大头教程-@ 艾木魁](https://www.bilibili.com/video/av29286614?from=search&seid=8554601692130722047)


[图标教程和背景图](https://tieba.baidu.com/p/4525730217)


-------------------


## 初始版本下载：

链接：https://pan.baidu.com/s/159eK-bAdhqXjvyhdbHWwrg 

提取码：c358 

## 更新补丁下载：

链接：https://github.com/grdaimap/wwnb-patch/repository/archive/master.zip

补丁包（改参数改图标修问题）

## 整合(=初始版+补丁)下载：

链接：暂无

提取码：暂无






