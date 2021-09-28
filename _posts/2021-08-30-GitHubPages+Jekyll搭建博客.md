---

layout: post

title: GitHub Pages + Jekyll 搭建博客

---

```
gem install jekyll
```



```
jekyll new blog
```



```
cd blog
```



```
jekyll server
```



![](http://img.kervin.cn/截图录屏_选择区域_20210830142015.png)



![](http://img.kervin.cn/截图录屏_选择区域_20210830142145.png)





![](http://img.kervin.cn/截图录屏_选择区域_20210830142623.png)



```
cd blog
```



```
git init
```



```
git add .
```



```
git commit -m "initial"
```



```
git remote add origin git@github.com:KervinChang/kervinchang.github.io.git
```



```
git push -u origin master
```



![](http://img.kervin.cn/截图录屏_选择区域_20210830164711.png)



```
http://jekyllthemes.org/
```



![](http://img.kervin.cn/截图录屏_选择区域_20210830165223.png)



![](http://img.kervin.cn/截图录屏_选择区域_20210830174051.png)



```
git clone https://github.com/alafighting/maupassant-jekyll.git maupassant
```



```
cd maupassant
```



```
jekyll build
```



```
jekyll server
```



```
vi _config.yml
```



```
# Site settings
title: 博客标题
subtitle: 博客副标题
description: 博客描述
baseurl: "" # the subpath of your site, e.g. /blog
url: "http://yourdomain.com" # 你的网址
domain: "yourdomain.com" # 你的域名
page_no_title: "No title" # 文章无标题时默认显示内容
beian: # "备案号"
email: email@yourdomain.com

# Build settings
markdown: kramdown

# Pageinate settings
page_size: 10 # 分页大小
paginate_path: ":num"

# Search settings
baidu_search: true
google_search: # true

# Menu settings
menu:
  - page: 首页
    directory: .
    icon: icon-home
  - page: 归档
    directory: archives/
    icon: icon-archive
  - page: 关于
    directory: about/
    icon: icon-about
  - page: 历史
    directory: history/
    icon: icon-history
  - page: 订阅
    directory: feed.xml
    icon: icon-rss

# Link settings
links: # 友情链接
  - title: site-name1
    url: http://www.example1.com/
  - title: site-name2
    url: http://www.example2.com/
  - title: site-name3
    url: http://www.example3.com/
```



```
cd _posts
```



```
# year-month-date-{post-slug}.{file-extension}
touch 2021-08-30-GitHubPages+Jekyll搭建博客.md
```



```
vi 2021-08-30-GitHubPages+Jekyll搭建博客.md
```



```
---
layout: post
title: GitHub Pages + Jekyll 搭建博客
---
```



![](http://img.kervin.cn/截图录屏_选择区域_20210830230031.png)



```
ping kervinchang.github.io
```



![](http://img.kervin.cn/截图录屏_选择区域_20210830231259.png)



![](http://img.kervin.cn/%E6%88%AA%E5%9B%BE%E5%BD%95%E5%B1%8F_%E9%80%89%E6%8B%A9%E5%8C%BA%E5%9F%9F_20210830231711.png)