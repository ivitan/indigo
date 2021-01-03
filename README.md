Base on [hexo-theme-indigo](https://github.com/yscoder/hexo-theme-indigo)
================

Material Design 风格的Hexo主题，基于 Hexo 3.0+ 制作。 [Preview](https://ivitan.com)

## New Feature
1. 添加代码块复制功能
2. 添加发布时间、继续阅读 Icon
3. 添加置顶功能
4. 修改代码块宽度显示
5. 修复 Item-Index 开启渲染时显示问题
6. 修复移动设备显示问题
7. 增加文章分类统计

## Feature

1. 仅支持 IE10+ 等现代浏览器。
2. 去 jQuery，更轻。相信现代浏览器的原生兼容性。
3. 使用 Less 作为 css 预处理器，需要安装 `hexo-renderer-less`。
4. 添加了英文字体支持 Roboto。
5. 添加了一些波纹效果。By [Waves](https://github.com/fians/Waves)
6. 无前端依赖的分享实现。
7. 基于静态数据的站内搜索，无第三方侵入。
8. 支持文章打赏。

## Useage
### Install
```git
cd ~/hexo-site
git clone https://github.com/ivitan/indigo.git themes/indigo

npm install hexo-renderer-less --save
npm install hexo-generator-feed --save
npm install hexo-generator-json-content --save
npm install hexo-helper-qrcode --save # 可选
```

### Post Pin
- Install

```sh 
cd ~/hexo-site
wget https://github.com/ivitan/ivitan.github.io/releases/download/Pin/generator.js -O ./node_modules/hexo-generator-index/lib/generator.js
```

- Useage

```sh
---
title: 
date: 
top: 101 # > 100
---
```


[文档 | Document](https://github.com/yscoder/hexo-theme-indigo/wiki)
