AndyCMS
=======

A old CMS System . If you need to install this project . First please create a database in you mysql . 
一个在大三的时候写的CMS系统，当时是结合Thinkphp加上比较流行的CSS3写的，主要体现在后台的一些功能。
<pre>
本框架是基于Thinkphp开发的一个小型CMS系统.
文件分布:
  前台	index.php
	后台	admin.php		账号admin	密码admin
	
	其余文件夹见Thinkphp详解
	
前台已经做了缓存功能:
	1 . 数据库字段缓存
	2 . 动态缓存首页数据库信息,每1小时后才从数据库提前最新文章等信息
	3 . 文章已经使用了静态缓存,生成静态html文件,1小时后自动清除
	
后台已做缓存功能
	1 . 显示最新文章,显示最新登录信息,显示最新评论记录等都设置为了1小时后提取数据库信息
	
	
注意事项: 
	如果后台登录页面的验证码不能显示出来,请执行killbom.php文件，这是由于BOM头造成.
</pre>
