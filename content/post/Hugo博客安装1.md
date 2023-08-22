---
title: "Hugo博客安装1"
date: 2023-08-22T13:44:32+08:00
draft: true
---

### 1. Hugo博客安装

```fallback
 1.前往 https://github.com/gohugoio/hugo/releases
 2.下载 hugo_X.XX_Windows-64bit.zip并解压到指定文件下(我的是D:\Hugo)
 3.将 hugo.exe 所在目录添加至系统环境变量
 4.hugo version验证是否安装成功(我的显示：hugo v0.117.0-b2f0696cad918fb61420a6aff173eb36662b406e windows/amd64 BuildDate=2023-08-07T12:49:48Z VendorInfo=gohugoio)
```

### 2. 建立站点并且设置主题

```fallback
1.hugo new site firstdemo//建立第一个项目
2.C:\Users\Administrator\firstdemo>git init;//进入项目中 初始化git
3.git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke;//添加主题
4.# 编辑 config.toml 配置文件使用该主题
5.在文件中添加theme = "ananke"
```

### 3.  创建一个新文件

```fallback
1.hugo new post/my-first-post.md
2.通过hugo server -D  启动项目并在本地:1313端口开启
```
