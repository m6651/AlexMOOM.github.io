# AlexMOOM.github.io
for personal blog web
# 如何发布新文章
<h3>一、新建.md文件</h3>
在AlexMOOM/AlexMOOM.github.io目录中找到_post文件夹，在_post文件夹内新建“*.md”文件
<h3>二、md文件命名格式：</h3>
要用“yyyy-mm-dd-name.md”命名md文件（name中“空格”和“-”等效），例如下列格式等价：
<li>1. 2018-07-02-hello-word.md</li>
<li>2. 2018-07-02-hello word.md</li>
将来网页打开该文章后，地址栏将显示的是https://AlexMOOM.github.io/2018/07/02/hello-word/
<h3>三、md文件内容格式：</h3>
md文件内开头加上：

<p>
---<br>
layout:     post   				    	# 使用的布局（不需要改）<br>
title:      My First Post 				# 标题 <br>
subtitle:   Hello World, Hello Blog 	# 副标题<br>
date:       2018-07-02 					# 时间<br>
author:     Merlin 						# 作者<br>
header-img: img/post-bg-20180702.jpg 	# 这篇文章标题背景图片<br>
catalog: true 							# 是否归档<br>
tags:									# 标签<br>
    - 生活<br>
    - 测试<br>
---<br>

</p>
以下开始正文写作：
<p># hey<br>
>这是我的第一篇博客。进入博客主页，新的文章将会出现在主页上.
</p>
