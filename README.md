# mabao-theme  for hexo
![](https://raw.githubusercontent.com/moretwo/hexo-theme/master/theme.gif)

[Ghost moretwo] hexo port, a really minimalist theme.
Preview: [live demo](http://moretwo.github.io)

## Installation
> 基于hexo 静态模版发布系统，fork hexo-theme-casper

### update
- 添加导航Nav
- 添加字体图标
- 修改样式style
- 改进theme

### Install

``` bash
$ git clone https://github.com/moretwo/hexo-theme.git
```

### Enable
```
myblog/themes/mabao-theme
```
Modify `theme` setting in `_config.yml` to `casper`.


## Configuration

``` 
# config
cover: /img/img-bg.jpg
logo: /img/logo.svg
bio: 作为挨踢业的伪设计狮伪技术牛 搬过砖也种过地：爱看、爱听、爱玩儿、爱折腾、机械水电、泥瓦木匠啥都来

# Content
excerpt_link: Read More

# Header  nav
menu:
  Home: /
  Archive: /archive
  Images: /images
  Wiki: /wiki
  Favorites: /favorites
  Contact: /contact

##Private: /private
##nav.fonticon.css
navclass:
 Home: icon-home
 Archive: icon-news
 Images: icon-image
 Wiki: icon-wiki
 Favorites: icon-Favorites
 Contact: icon-mail

##Private: icon-lock
rss: /atom.xml

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
google_plus:
fb_admins:
fb_app_id:
```





## Original Casper Copyright & License ##

Copyright (C) 2013 Ghost Foundation - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


[Ghost]: http://github.com/tryghost/ghost/
[Ghost Casper]: https://github.com/moretwo/hexo-theme
