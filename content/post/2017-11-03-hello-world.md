---
layout:     post 
title:      "Welcome to Zhaohuabing Blog"
subtitle:   "Hello World, Hello Blog"
date:       2017-11-04
author:     "赵化冰"
URL: "/2017/11/03/hello-world/"
image:      "https://img.zhaohuabing.com/post-bg-2015.jpg"
---

> “Yeah It's on. ”


## Hello World!

前面三个-中间的内容叫front matter，是文章的基本信息，每个文章都要有

 layout是页面的模板，对于文章来说一般就是post
 title，subtitle就不用说了
 date是创建日期
 URL是文章的链接
 img是banner图片，可以用这种图床链接也可以用自己的图片

网站里所有的图片都放在/static/img下面，也可以新建文件夹OK，但是要在static下面，引用的时候路径是相对于static的，比如

![example image](/img/404-bg.jpg)

pdf也是一样的，有时候预览会卡住，ctrl+C停止之后再hugo server就好了

文章是markdown的格式，这个有了解吗：没有了解

简单来讲就是通过不同标记表示不同格式

# 这是一级标题

## 🎧标题

### 记得加空格才是标题

征文，ababbaba，**粗体**，*斜体*，

>it's quote

1. item1
2. item2
3. ...

- unordered list item1
- unordered list item 2
- like this

---

seperate line

[link text](https://google.com)
wow!!HAODE!

two blank makes a line feed
abababba

another paragraph

it's a table
|table 1|table heading 2| |
|:-|:-:|-:|
|left align|center|right aligned|

some `codes` here

```C
#include <stdio.h>
int main(){
    int a, b;
    return 0;
}
// it's a code block
```

- [ ] todo list
- [x]checked todo

haiyou haoduo nikeyi manmankan HAODELAOSHI
