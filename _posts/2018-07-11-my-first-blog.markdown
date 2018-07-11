---
layout: post
title:  "Finally the first blog"
date:   2018-07-11 17:12:00 +0800
categories: personal
---
After hours of work with a slow Internet, I think I finally got the basic things of jekyll. Otherwise you will not see this page.

Quite a lot of instructions can be found from baidu.com. But I was still faced with some problems:

* Installation of Ruby should be with the DevKit, otherwise you cannot go on. I thought that I would not use Ruby to develop anything. So I chose the version without DevKit first. Do not follow me!

* MSYS2 is really large and can hardly be accessed in China within the GFW. The Ruby installation program will automatically download it from the official website and it can be really slow. I mannually installed it from mirrors.tuna.tsinghua.edu.cn. This site also helps you to set the pacman in MSYS2 so that other packages can be downloaded within GFW.

* It seems that the Ruby 2.4.4 installer will not set the PATH automatically. You should manually set it.

* Remember, the name of the post file should begin with the date, otherwise jekyll will not know it. (Why in such a way?)