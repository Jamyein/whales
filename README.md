# July-Q

### 该主题魔改自 [hexo-theme-july](https://github.com/wisp-x/hexo-theme-july)主题，并进行一定的维护。

---

<center><img src="./source/img/preview.png"></center>

支持版本
--------
```
Hexo:7.2.0
```

魔改内容
--------

1. 增加 waline 评论系统
2. 修改超链接色彩
3. 增加文章底部导航栏
4. 增加文章表头作者和分类等信息
5. 修改字体为雾鹭文楷
6. 修改引用和代码块样式
7. 修复在其他浏览器中CSS文件加载失败的问题
8. 去掉了banner头图
9. 添加主页作者标签和格言
10. 主页增加社交媒体链接跳转
11. 精简代码
12. 修复开启简约翻译时导致的头像错位
13. 适配深色模式自动切换


Install
-------

```
$ git clone https://github.com/Jamyein/july-q.git themes/july-q
```

```
$ git subtitle add https://github.com/Jamyein/july-q.git themes/july-q
```


Enable
------

Modify theme setting in _config.yml to july-q

```
...
theme: july-q
...
```


Create Page
-----------

```
$ hexo new page about
```

Update
------

```
cd themes/july-q
git pull
```

Configuration
-------------

```
# html lang
language: zh-CN

# main menu navigation
menu:
  主页: /index.html
  归档: /archives/index.html
  关于: /about/index.html

site:
  avatar: /img/avator.jpg # head portrait.

social:
  enable: true # true to enable the social media link, show you link to it.
  rss: /atom.xml
  github: https://github.com/Jamyein
  email: https://citrusea.cc/email/index.html

# stylesheets loaded in the <head>
stylesheets:
  - /css/markdown.css
  - /css/july.css
  - /css/waline.css # if use waline, please delete the "#" to use the waline.css

# scripts loaded in the end of the body
scripts:
  - /js/jquery-3.7.0.min.js

# atom: atom.xml # website feed. Suggested plugin for hexo about feeds.

favicon: /img/favicon.ico # you can change to you ico

waline: 
  enable: true # true to enable the waline
  serverURL: # your comment server url

since:2023 #You can modify here to change the copyright information at the bottom of the page.
```

Licence
-------

MIT
