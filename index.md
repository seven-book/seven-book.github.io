---
layout: default
title: 首页
---

<div>
<div class="span4">
<a href="/2022/08/21/kamailio-in-action.html">
<img style="align-self: center;" src="/images/kamailio-in-action.jpg" />
</a>
</div>
<div class="span4">
<img style="align-self: center;" src="/images/fsdg.jpg" />
</div>
<div class="span4">
<img style="align-self: center;" src="/images/pg9x.jpg" />
</div>
</div>

<br style="clear: both"/>
<br style="clear: both"/>

- **《Kamailio实战》**：机械工业出版社/2022-09/杜金房 吕佳娉 著/299页/16开/ISBN：978-7-111-71247-3 这是[购书链接](https://mp.weixin.qq.com/s/UjD5hV3h9AZlCow9kjQUmQ)。

- **《FreeSWITCH权威指南》**：机械工业出版社/2014-06-01/杜金房 张令考 著/644页/16开/ISBN：978-7-111-46626-0

**您也可以用微信扫描右侧或下方的小樱桃科技微信公众号二维码通过小樱桃商城直接购买**。

<div class="mobile-only">
<img style="align-self: center;" src="/images/xyt.jpg" />
<br/>
小樱桃科技微信公众号
<br/>
<br/>
</div>

也可以从这些网站购书：

<!-- [有赞商城](http://wap.koudaitong.com/v2/showcase/goods?alias=vmrygm92&activity=&ps=320) -->

[豆瓣](https://read.douban.com/reader/ebook/15303799/)（电子书）
| [金书网](http://www.golden-book.com/booksinfo/17/1753082.html)
| [京东](http://item.jd.com/11472569.html)（纸书+电子书）
| [亚马逊](http://www.amazon.cn/FreeSWITCH%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97-%E6%9D%9C%E9%87%91%E6%88%BF/dp/B00KMJ2OOY/qid=1401772222&sr=8-1&keywords=FreeSWITCH%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97#)（纸书+电子书）
| [当当网](http://product.dangdang.com/23486629.html#ddclick?act=click&pos=23486629_0_0_q&cat=&key=FreeSWITCH%C8%A8%CD%FE%D6%B8%C4%CF&qinfo=1_1_48&pinfo=&minfo=&ninfo=&custid=&permid=20140210213048766540706674106335572&ref=http%3A%2F%2Fwww.dangdang.com%2F&rcount=&type=&t=1401772355000)（有纸质版和电子版）
| [互动出版网](http://product.china-pub.com/3770217)
| [淘宝网](http://s.taobao.com/search?q=FreeSWITCH%C8%A8%CD%FE%D6%B8%C4%CF&commend=all&ssid=s5-e&search_type=item&sourceId=tb.index&spm=1.7274553.1997520841.1&initiative_id=tbindexz_20140604)
| [多看](http://www.duokan.com/book/52410)（电子版）


<br style="clear:both">

请关注右侧「小樱桃科技」微信公众号，可以找到以下电子书的购买方式。这里有一些[精美封面](/2020/03/21/FreeSWITCH-ebooks.html)。

* 《FreeSWITCH VoIP实战》 
* 《FreeSWITCH文集》
* 《FreeSWITCH互联互通》
* 《FreeSWITCH Wireshark》
* 《FreeSWITCH实例解析》
* 《FreeSWITCH源代码分析》

**购买方式**：

* 小樱桃商城　　　　－　可微信支付购买
* RTS VIP知识星球　－　付费加入后可免费阅读

<br style="clear:both">

如果您还不了解Kamailio，请到这里参观：<http://www.kamailio.org.cn> 。

如果您还不了解FreeSWITCH，请到这里参观：<http://www.freeswitch.org.cn> 。
<br>

<hr>

## 最新动态


<ul class="posts">
  {% for post in site.posts limit:30 %}
    <li class="post-list"><span>{{ post.date | date: "%Y-%m-%d" }}</span> &rarr;
    <a href="{{ post.url }}"><strong>{{ post.title }}</strong></a>
    {% for tag in post.tags limit:30 %}
      <span style="color:#999">&nbsp;&nbsp;|&nbsp;&nbsp;{{ tag }}</span>
    {% endfor %}
    </li>
  {% endfor %}
    <li class="post-list"><span><a href="/posts.html">更多文章...</a></span></li>
</ul>

<br><br>
