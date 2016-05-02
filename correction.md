---
title: 勘误
layout: default
---

# {{ page.title }}

本页是《FreeSWITCH权威指南》的勘误页面，欢迎提意见。请直接在本页面留言，或发邮件到 freeswitch .at. dujinfang.com ，谢谢。

注：Px Ly = 第x页第y行（L-y即倒数第y行）

<br>
<br>

**特别提示**：注意，严格说来这一条不算勘误，FreeSWITCH的代码库在本书出版后发生了迁移，因此书中所有 git://git.freeswitch.org/freeswitch.git 均改为 https://stash.freeswitch.org/scm/fs/freeswitch.git ，参见：[FreeSWITCH代码库地址更新](2014/07/12/freeswitch-git-repo-change.html) 。

<br>
<br>

【更新时间：2016年5月2日】

* P50 L3

    原为：http://files.freeswitch.org/freswitch-1.2.10.tar.gz

    改为：http://files.freeswitch.org/freeswitch-releases/freeswitch-1.2.10.tar.bz2

【更新时间：2016年3月31日】


* P533 L6

	原文：Channnel

	改为：Channel

【更新时间：2016年3月9日】

* P71 L-16
 
    原文：event_socekt.conf.xml

    改为：event_socket.conf.xml


【更新时间：2016年3月2日】

* P439 L5

    原文：`say:please say yes or no`

    改为：`say:'please say yes or no'`

* P439 L15

    原文：`<action application="play_and_detect_speech" data="say:please say yes or no detect:pocketsphinx yes_no"/>`

    改为：`<action application="play_and_detect_speech" data="say:'please say yes or no' detect:pocketsphinx yes_no"/>`

* P100 L1

    原文：default 和 include 目录

    改为：default 和 public 目录

* P102 L-13

    原文：`<action application="log" data="INFO The last few digits is $1"/>`

    改为：`<action application="log" data="NOTICE The last few digits is $1"/>`

* P130 L-4

    原文：请抽空请

    改为：抽空请

* P146 图708

    Rob应改为Bob

* P148 L1

    原文：会放描述协议

    改为：会话描述协议

* P268 L-8

    原文：`<action application="set" data="hold_music=$${hold_music}"/>`

    改为：`<action application="set" data="fifo_music=$${hold_music}"/>`

* P283 -2, -3

    原文： GSM,GSM  (重复)

    改为： GSM

P355 图B

    原文： B(Transferee)

    改为： B(Transferor)

* P366 L12

    原文少一个空格

    改为：`<action application="bridge" data="sofia/gateway/gw${distributor(dist1)}/$1" loop="2"/>`



* P318 中间位置

    原文：`gw\+xyt`

    改为：`gw\+gw_A`

* P406 L16

    原文：`print( people[ 10 ] )                      --> "Some Dude"
`

    改为：`print( people[ 7 ] )                      --> "Some Else"
`

* P409 L-11
    原文：`local dest_number = seesion:getVariable("context")`
    改为：`local context = seesion:getVariable("context")`



【更新时间：2014年8月18日】

* P78 图5-1最上面

    原文：符合识别

    改为：语音识别

* P158 L-10

    原文：超短

    改为：越短

* P158 L-9

    原文：超长

    改为：越长

* P216 L-3

    原文：PCMU'}

    改为：PCMU}

* P215 L-14 最后一段代码第二行

    原文：`&echo`

    改为：`echo`

* P240 L8

    原文：channeL_uuid

    改为：channel_uuid

* P356 L-10

    原文：继续与B通话

    改为：继续与A通话

* P356 L-8到L-7

    原文：并按3，则可以形成三方通话，大家一起说。还有更有意思的，B还可以随时按1与A通，按2与C通，而让A与C永远不通……

    改为：并按0，则可以形成三方会议电话，大家一起说。当然B在会议模式中还可以随时按`#`号键挂掉与C，继续跟A通话。


【更新时间：2014年7月14日】 （以下内容已于2014年8月再版时改正）


* PIX L-3 前言特别鸣谢部分：

    原文：漏掉了 “Newrock（迅时）”

    改为：Yealink(亿联)、Grandstream(潮流)、Newrock（迅时）、Dinstar(鼎信通达)、Sangoma(加拿大, 及中国总代星昊通)、Vestec(加拿大)等。

* P7 L8

    原为：第三方伙伴计划

    改为：第三代合作伙伴计划

* P7 脚注六，排版多了个空格

    原为：http://zh.wikipedia.org/wiki/ 长期演进技术

    改为：http://zh.wikipedia.org/wiki/长期演进技术

* P16 L-3

    原为：ReleaseGard

    改为：ReleaseGuard

* P21 L-1

    原为：MEGACO

    改为 Megaco

* P81 L-11

    原为：这些不接口

    改为：这些接口

* P89 图5-1

    原为：符合识别

    改为 语音识别

    原为：XMT接口

    改为：XML接口


* P136 图7-6 第4、5个箭头方向画反

    原为：200 OK 向右，ACK 向左

    改为：200 OK 向左，ACK 向右

* P150 L1

    原为：Badwidth

    改为：Bandwidth


* P233 L-7：少了一个双引号

    原为  `inline="true/>`

    改为  `inline="true"/>`


* P327 备注三 L-2

    原为：FSX

    改为：FXS

* P335 L10

    原为：我们将按图14-8所示的拓扑结构来搭建实验环境。

    改为：下面，我们首先来搭建一个简单的模拟实验环境。

* P348 L-7

    原为：前者基于H323plus库，后者基于Opal库

    改为：前者基于Opal库，后者基于H323plus库

* P360 L13

    原为：控制端口号，默认为6001

    改为：控制端口号，默认为6061

* P361 L3

    原为：`<action application="esf_page_group" data="esf_page_group 224.0.0.100 34567 6001"/>`

    改为：`<action application="esf_page_group" data="224.0.0.100 34567 6061"/>`


* P386 L9

    原为：时毛

    改为：时髦

* P394 L8

    原为： `&eccho`

    改为：`&echo`

* P409 L-5

    原为：getUUID

    改为：get_uuid

* P409 L-4

    原为：get_uuid(])

    改为：get_uuid()

* P432 L-1： 原链接已失效

    改为 <http://fisheye.freeswitch.org/browse/freeswitch-contrib/seven/lua/batch_dialer.lua?hb=true>

<br>
<br>
<br>

<!--高速版，加载速度快，使用前需测试页面的兼容性-->
<div id="SOHUCS"></div>
<script>
  (function(){
    var appid = 'cyrbxBE9W',
    conf = 'prod_7cafa4a3aa6ae67880a614a6ee14161f';
    var doc = document,
    s = doc.createElement('script'),
    h = doc.getElementsByTagName('head')[0] || doc.head || doc.documentElement;
    s.type = 'text/javascript';
    s.charset = 'utf-8';
    s.src =  'http://assets.changyan.sohu.com/upload/changyan.js?conf='+ conf +'&appid=' + appid;
    h.insertBefore(s,h.firstChild);
    window.SCS_NO_IFRAME = true;
  })()
</script>
