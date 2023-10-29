---
title: 阿里云OSS + PicGo上传图片失败问题解决
date: 2023-10-22 19:44:14
tags:
---
# 先宣布一个好消息！
图床终于搭好了。
在尝试了gitee,github后，终于还是决定自己搭建图床。
因为gitee不知为何用不了，github太慢了。
我参考的这个教程

# 遇到的问题
**上传失败**!这应该是所有图床搭建时最普遍的问题了吧。

搭建教程总体参考这篇博客[我花 9 块钱搭了一个配合个人博客使用的个人图床](https://sspai.com/post/56116)

总体还是非常顺利的，购买、配置，到最后终于要使用PicGo上传了，结果：**上传失败**

因为右下角picgo弹出的小窗没有显示错误信息，所以我不知道是哪里出了问题，只能搜索上传失败怎么办，但网上大多教程都是由于配置出现问题，如多敲了空格等等。（现在想想编译器能够告诉我们哪里出现了语法错误可真是好！）多次检查我的配置没写错后，发现原来PicGo是有日志的。
于是我打开了日志
打开步骤如图
![](https://bozhiblogimage.oss-cn-beijing.aliyuncs.com/pic/picgo1.png)

日志文件显示这么一段：
![](https://bozhiblogimage.oss-cn-beijing.aliyuncs.com/pic/PicGoLog.png)
看不太懂，或者没耐心看，于是直接复制给了chatGPT，问他为什么上传不了。
![](https://bozhiblogimage.oss-cn-beijing.aliyuncs.com/pic/PicGoLogGPT.png)

原来是windows时间不标准导致了这个问题！！！

# 感想
话说回来，自从装了双系统ubantu，上完ubantu再上windows时间经常会出错，但也没太在意。
谁能想到，居然设备的时间也会导致上传失败呢。一切都很顺利，但老天总是想让我不顺利一点。解决了就好，哈哈哈！