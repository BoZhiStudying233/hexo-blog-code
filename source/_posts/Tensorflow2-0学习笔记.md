---
title: Tensorflow2.0学习笔记
date: 2023-11-19 13:22:37
tags:
---
# 前言
参考教材：https://www.bilibili.com/video/BV1B7411L7Qt?p=1&vd_source=eb8db86881f9d0e921f94dd2a4155bc9
Tensorflow版本：Tensorflow2.4
CUDA:暂未安装

---
# 遇到的问题与解决
## 用pycharm新建工程时候解释器添加失败。
我的界面是下面这样
![](https://bozhiblogimage.oss-cn-beijing.aliyuncs.com/pic/20231119213006.png)
视频中是下面这样的，但我在我的anaconda3的TF2.1路径下根本找不到python.exe
![](https://bozhiblogimage.oss-cn-beijing.aliyuncs.com/pic/20231119212817.png)
在旁边工位的曾阳的帮助下，设置成这样即可。
![](https://bozhiblogimage.oss-cn-beijing.aliyuncs.com/pic/20231119212730.png)
可以在condabin文件下找到一个bat文件，然后更改```Use existing environment```为TF2.1即可


