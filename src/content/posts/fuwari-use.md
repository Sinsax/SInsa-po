---
title: Fuwari使用
published: 2025-08-19
description: '一些Fuwari使用技巧记录'
image: ''
tags: [指南,Fuwari]
category: 'Fuwari'
draft: false 
lang: ''
---

# 本地运行，参考效果
```bash
#安装依赖项
pnpm install

#运行
pnpm run dev
pnpm dev

```


# 新建post

```bash 
pnpm new-post 名称
```

若需要插入图片，新建文件夹并改名为index.md

>* `newpost.md`

>- newpost
>   - `index.md`
>   - `picture.jpg`

或
>- newpost
>   - `index.md`
>   - image
>       - `picture.jpg`


# 图片追加
```ts
//md文件内添加
![](image/chibiysyk.gif)
```
## 参考
[markdown语法](https://markdown.com.cn/basic-syntax/)
