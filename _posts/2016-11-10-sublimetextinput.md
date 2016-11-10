---
layout: post
title: Ubuntu下sublime text 3不能输入中文
date: 2016-11-10
tags: 工具   
---

+ 更新并升级系统为最新(较新的系统会解决很多可能出现的问题)（非必须）

```bash
sudo apt-get update && sudo apt-get upgrade
```

+ 克隆项目到本地 :

```bash
git clone https://github.com/lyfeyaj/sublime-text-imfix.git
```

+ 运行脚本:

```bash
cd sublime-text-imfix && ./sublime-imfix
```

+ 完成! 重新启动后就可以在 Sublime Text 2/3 中 使用 Fcitx了! 注意: 皮肤可能需要自己选择 ^_^