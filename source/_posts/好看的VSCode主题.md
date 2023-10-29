---
title: 好看的VSCode主题
date: 2023-10-22 20:10:38
tags:
---
推荐一下自己的VSCode主题，以后自己换机了也可以参考这个设置主题。
# 预览
![](https://bozhiblogimage.oss-cn-beijing.aliyuncs.com/pic/VSCodeTheme.png)
# 配置步骤
## 插件
### Material Theme
![](https://bozhiblogimage.oss-cn-beijing.aliyuncs.com/pic/VSCode-MaterialTheme.png)
安装后点击设置颜色主题
![](https://bozhiblogimage.oss-cn-beijing.aliyuncs.com/pic/VSCode-MaterialTheme1.png)
设置Material Theme Darker High Contrast主题（我感觉这个不错）
### Material Theme Icons
![](https://bozhiblogimage.oss-cn-beijing.aliyuncs.com/pic/VSCode-MaterialThemeIcons.png)
设置文件图标主题，选择第一个
![](https://bozhiblogimage.oss-cn-beijing.aliyuncs.com/pic/VSCode-MaterialThemeIcons1.png)

## 修改注释颜色
游戏我们改变了主题，注释变得不太明显
![](https://bozhiblogimage.oss-cn-beijing.aliyuncs.com/pic/VSCode-CommentsObvious.png)
这对于一些多注释的程序可能不太友好，但我们可以手动更改注释颜色
具体步骤为：打开字体的setting.json文件，将以下代码添加到最后一个"}"的前面
```json
    "editor.tokenColorCustomizations": {
        "comments": "#3dca3d"
    }
```
如图
![](https://bozhiblogimage.oss-cn-beijing.aliyuncs.com/pic/VSCode-FontSetting.png)
其中的```#3dca3d```表示颜色，可以自己更改，我觉得改成这个绿色比较明显美观度也挺好看。
# 结束！