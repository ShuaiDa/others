
# 注意

1. 修改`/pages/about.md`中关于我的内容

2. 适当修改`/_config.yml` 文件，具体作用请参考注释

3. 清空`/_posts`目录下文件和`/post`目录下文件

4. 网站的 logo 放在了`/static/img/`下

5. 最后，如果你把项目 fork 过去了，想要删除我的提交记录可以先软重置到第一个提交，然后再提交一次，最后强制推送一次就行了

# 使用

文章放在`/_posts`目录，命名为`yyyy-MM-dd-xxxx-xxxx.md`，内容格式如下

```
---
layout: mypost
title: 标题
categories: [分类1,分类2]
---

文章内容，MD格式
```

文章资源放在`/posts`目录，如文章标题是`20xx-05-27-theme-user.md`，则该篇文章的资源放在`/posts/20xx/05/27`下,在文章使用时直接引用即可

```

