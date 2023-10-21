---
title: "{{ replace .Name "-" " " | title }}"   #新建markdown博客模板
date: {{ .Date }}
lastmod: {{ .Date }}
author: ["hjroyal"]
keywords: ["",""]
categories: ["",""] # 没有分类界面可以不填写
tags:  # 标签
- tag
series: [""] # 系列
description: ""
weight:  #值越小首页越靠前
slug: ""  # 使用 slug属性 来作为当前文章的有效 url 的末尾部分 ；如果没有提供 slug 则使用 title 代替。
draft: false # 是否为草稿
comments: true # 本页面是否显示评论
reward: false # 打赏
mermaid: true #是否开启mermaid
showToc: true # 显示目录
TocOpen: true # 自动展开目录
hidemeta: false # 是否隐藏文章的元信息，如发布日期、作者等
disableShare: false # 底部不显示分享栏
showbreadcrumbs: true #顶部显示路径
outer: false # true 表示是转载
math: true #latex
cover:
    # image: "" #本地图片路径例如：/posts/tech/123/123.png 
    image: "https://source.unsplash.com/random/940x400?sunshine"  #随机图片
    caption: "" #图片底部描述
    alt: ""
    relative: false
---
