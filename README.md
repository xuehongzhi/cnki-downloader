你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
# Overview
This is a free downloader for CNKI, you can search, download papers , journals, conference records in caj/pdf/.. formats (that 
means you should use [**CAJViewer**](http://www.portablesoft.org/cajviewer-lite/) to open the document).

BTW:
- *no matter what this project always will die*
- *star please* :)

# Download
The Latest Release (2017-3-11 **v0.8-alpha**):
+ [Windows Portable](https://github.com/amyhaber/cnki-downloader/releases/download/v0.8-alpha/cnki-downloader-windows.zip)
+ [Linux Portable](https://github.com/amyhaber/cnki-downloader/releases/download/v0.8-alpha/cnki-downloader-linux.zip)
+ [Mac Portable](https://github.com/amyhaber/cnki-downloader/releases/download/v0.8-alpha/cnki-downloader-darwin.zip)

# FAQ
- Q：**为什么不开发/增加XXX功能？**

  A：这只是随手写的一个工具，并没有考虑做成完善的东西，如之前所言，这程序所用的接口迟早会被封的，所以将就用吧

- Q：**为什么检索不到XXX文章？**

  A：服务器上相应的条目被下线了，再次重申，这程序所用的接口访问的**不是知网主库**
  
- Q：**为什么下载时出现Bad Request 400？**

  A：知网的土豆服务器又炸了，请坐等他们修复

- Q：**为什么有些文档是PDF格式，有些是CAJ？**

  A：此程序所使用的接口无法选择文档格式，所以只能下到什么算什么

- Q： **为什么无法解压程序包？**

  A： 请使用最新的解压软件，如7zip等

# Usage
Here is a gif picture, you can follow it, and it's really easy

![image](https://github.com/amyhaber/cnki-downloader/blob/master/screenshots/showcase2.gif)

# Future Work
+ Fix bugs
