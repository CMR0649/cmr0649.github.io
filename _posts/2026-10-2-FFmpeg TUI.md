---  
title: FFmpeg TUI  
date: 2026-10-2 14:02:11 +0800  
categories: [教程]  
tags: [ffmpeg-tui]  
---  
## 介绍  
FFmpeg TUI 是一个用于 FFmpeg 的终端用户界面，已开源至GitHub：  
**[https://github.com/CMR0649/ffmpeg-tui](https://github.com/CMR0649/ffmpeg-tui)**  

![Desktop View](/assets/post_imgs/ffmpeg-tui-1.png)
_FFmpeg TUI 文件界面_

## 使用  

### 获取相关文件  
首先，从 [Releases](https://github.com/CMR0649/ffmpeg-tui/releases)获取可执行文件  
此外，还需获取 FFmpeg ，Windows 用户可以在 [gyan.dev](https://www.gyan.dev/ffmpeg/builds/ffmpeg-git-full.7z) 获取  
Linux 用户可从包管理器获取，或下载[由BtbN构建的二进制文件](https://github.com/BtbN/FFmpeg-Builds/releases)  
> 在 GitHub 文件链接前加`https://gh.ifxog.cc.cd/`可加速下载
{: .prompt-tip }

### 相关配置
> 记得保存！ 
{: .prompt-tip }  
FFmpeg TUI 默认从环境变量中读取 FFmpeg 路径，也可以在设置中手动指定 FFmpeg 路径  

在预设界面可以添加自定义命令，例如：
```
ffmpeg -i input output.mkv
```
`input`为输入文件，`output`为输出文件，`.mkv`为后缀名，可按需替换  

关于各种选项如何选择，建议阅读[终末诗](https://www.zhihu.com/people/zhong-mo-shi)的教程：  
[小刻也能看懂的视频压缩入门四万字超大型科普](https://zhuanlan.zhihu.com/p/1913258114746122747)  
觉得太长可以看  
[维什戴尔也能看懂的视频压缩5000字入门](https://zhuanlan.zhihu.com/p/1943027518480294814)  
