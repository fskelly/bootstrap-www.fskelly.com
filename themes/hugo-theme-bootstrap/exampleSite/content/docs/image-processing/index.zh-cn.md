+++
title = "图像处理"
date = 2021-08-15T14:19:06+08:00
draft = false
comment = true
toc = true
reward = true
carousel = true
categories = [
  "Markdown"
]
tags = [
  "图像"
]
series = [
  "文档"
]
aliases = [
  "/zh-cn/posts/image-processing"
]
[menu.footer]
  parent = "features"
  weight = 2
+++

本文提供一些调整图片大小和对齐图片的用例。

<!--more-->

## 调整图片大小

我们利用 URL 的查询字符串来调整图片大小。

### 指定宽度和保留比率

```markdown
![Resize](featured-sample.png?width=300px)
```

![Resize](featured-sample.png?width=300px)

### 指定高度和保留比率

```markdown
![Resize](featured-sample.png?height=200px)
```

![Resize](featured-sample.png?height=200px)

### 指定宽度和高度

```markdown
![Resize](featured-sample.png?width=300px&height=200px)
```

![Resize](featured-sample.png?width=300px&height=200px)

> 它不仅可以用于[页面资源](https://gohugo.io/content-management/page-resources/)，而且也适用于 **static** 图像和外部图像。
> 但是，除了页面资源外，其他资源的大小都是按内联样式调整的，也就是说，它们的原始大小不会改变。

## 对齐图像

我们可以利用 URL 片段轻易地对齐图像，比如：`#center`, `#floatleft` 和 `#floatright` 分别表示居中对齐、向左浮动和向右浮动。

### 居中对齐

添加 `#center` 使图片居中对齐。

举个例子：`![Center](/center.png#center)`。

![Center](/featured-sample.png?height=120px#center)

### 向左浮动

![Float Left](/featured-sample.png?height=120px#floatleft)

添加 `#floatleft` 使图片向左浮动。

举个例子：`![Float Left](/featured-sample.png#floatleft)`。

### 向右浮动

![Float Right](/featured-sample.png?height=120px#floatright)

同样的，我们也可以添加 `#floatright` 使图片向右浮动。

举个例子：`![Float Right](/featured-sample.png#floatright)`。
