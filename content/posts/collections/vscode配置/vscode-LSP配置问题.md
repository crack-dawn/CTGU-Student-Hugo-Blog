---
title: Vscode LSP补全
subtitle:
date: 2024-08-12T13:00:30+08:00
slug: 2bf712f
draft: false
comment: true
summary:
description:
keywords:

message:   # 密码输入框预设提示
password:  # 解锁密码

layout:     # 布局归类：posts, archives, tags, categories等，文件分散在不同文件夹需要注明
archives:
tags: ['vsocde']
categories: ['vsocde配置']
collections: ['vsocde配置']

author:
  name:
  link:
  email:
  avatar:
license:
repost:
  enable: true
  url:

weight: 0
hiddenFromHomePage: false
hiddenFromSearch: false
hiddenFromRss: false
hiddenFromRelated: false

resources:
  - name: featured-image
    src: featured-image.jpg
  - name: featured-image-preview
    src: featured-image-preview.jpg
toc: true
math: true
lightgallery: true

# See details front matter: https://fixit.lruihao.cn/documentation/content-management/introduction/#front-matter
---
## [vsocde task Documents](https://code.visualstudio.com/Docs/editor/tasks)
<!--more-->


# markdown 与一些代码补全问题

+ 打开VScode的setting.json在[markdown]下新增或修改editor.quickSuggestions即可：

    ```json
    {
        "[markdown]": {
            "editor.quickSuggestions": {
                "other": "on",
                "comments": "on",
                "strings": "on"
            },
        }
    }
    ```


 