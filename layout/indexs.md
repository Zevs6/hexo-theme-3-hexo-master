# Why Blog

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=600 height=86 src="//music.163.com/outchain/player?type=2&id=552200483&auto=1&height=66"></iframe>
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=600 height=86 src="//music.163.com/outchain/player?type=2&id=1313179453&auto=0&height=66"></iframe>


## 对博客的理解

喜欢写Blog的人，会经历三个阶段。
> 第一阶段，刚接触Blog，觉得很新鲜，试着选择一个免费空间来写。

>第二阶段，发现免费空间限制太多，就自己购买域名和空间，搭建独立博客。

>第三阶段，觉得独立博客的管理太麻烦，最好在保留控制权的前提下，让别人来管，自己只负责写文章。

我们每个人的在网络上产生的数据越来越多，这些信息是我们在互联网上存在过的痕迹，值得我们认真对待。但是它们被分散分布在各个网站上。很多时候我们很难将它们聚合在一起，而且各个网站的信息排布方式也没有办法自由控制，所以我们需要一个可以由自己主宰的空间——博客。

通过博客，我们可以记录自己的生活和成长的轨迹。它不像 Twitter 那样碎片化，也不像 Facebook 那样关系化，它是私人的空间。

## 关于Zevs
**Zevs** 是阿帅（张  帅）的个人站。

到目前为止已经写了<code class="article_number"></code>篇文章， 共<code class="site_word_count"></code>字。

本站访问人数：<code class="site_uv"></code>人次 ， 访问量：<code class="site_pv"></code>次

<code id="sitetime"></code>

<script language=javascript>
	function siteTime(){
		window.setTimeout("siteTime()", 1000);
		var seconds = 1000;
		var minutes = seconds * 60;
		var hours = minutes * 60;
		var days = hours * 24;
		var years = days * 365;
		var today = new Date();
		var todayYear = today.getFullYear();
		var todayMonth = today.getMonth()+1;
		var todayDate = today.getDate();
		var todayHour = today.getHours();
		var todayMinute = today.getMinutes();
		var todaySecond = today.getSeconds();
		/* Date.UTC() -- 返回date对象距世界标准时间(UTC)1970年1月1日午夜之间的毫秒数(时间戳)
		year - 作为date对象的年份，为4位年份值
		month - 0-11之间的整数，做为date对象的月份
		day - 1-31之间的整数，做为date对象的天数
		hours - 0(午夜24点)-23之间的整数，做为date对象的小时数
		minutes - 0-59之间的整数，做为date对象的分钟数
		seconds - 0-59之间的整数，做为date对象的秒数
		microseconds - 0-999之间的整数，做为date对象的毫秒数 */
		var t1 = Date.UTC(2019,08,13,00,00,00); //北京时间2018-2-13 00:00:00
		var t2 = Date.UTC(todayYear,todayMonth,todayDate,todayHour,todayMinute,todaySecond);
		var diff = t2-t1;
		var diffYears = Math.floor(diff/years);
		var diffDays = Math.floor((diff/days)-diffYears*365);
		var diffHours = Math.floor((diff-(diffYears*365+diffDays)*days)/hours);
		var diffMinutes = Math.floor((diff-(diffYears*365+diffDays)*days-diffHours*hours)/minutes);
		var diffSeconds = Math.floor((diff-(diffYears*365+diffDays)*days-diffHours*hours-diffMinutes*minutes)/seconds);
		document.getElementById("sitetime").innerHTML="网站已运行"+diffYears+" 年 "+diffDays+" 天 "+diffHours+" 小时 "+diffMinutes+" 分钟 "+diffSeconds+" 秒";
	}/*因为建站时间还没有一年，就将之注释掉了。需要的可以取消*/
	siteTime();
</script>

## 博客平台
这个博客通过 [Hexo](https://hexo.io/) 生成，部署在 [GitHub Pages](https://pages.github.com/)，主题 [3-hexo](https://github.com/yelog/hexo-theme-3-hexo) 已经在github上开源

主要功能：
- 搜索支持文章标题、标签(#标签)、作者(@作者)
- pad/手机等移动端适配
- 页面全局快捷键 <a href='http://yelog.org/2017/03/24/3-hexo-shortcuts/'>3-hexo快捷键说明</a>

> 如果喜欢卡哇伊点的可以访问  [**喵绪~**](http://z.zhsh666.xyz)

<script>
var _hmt = _hmt || [];
(function() {
  var hm = document.createElement("script");
  hm.src = "https://hm.baidu.com/hm.js?9143eb90f928be2d7df47517e5f3de98";
  var s = document.getElementsByTagName("script")[0]; 
  s.parentNode.insertBefore(hm, s);
})();
</script>