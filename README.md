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



# From https://github.com/hexojs/hexo/
## More Information

- Read the [documentation](http://hexo.io/)
- Find solutions in [troubleshooting](http://hexo.io/docs/troubleshooting.html)
- Join discussion on [Google Group](https://groups.google.com/group/hexo)
- See the [plugin list](https://github.com/hexojs/hexo/wiki/Plugins) and the [theme list](https://github.com/hexojs/hexo/wiki/Themes) on wiki
- Follow [@hexojs](https://twitter.com/hexojs) for latest news

## License
MIT

[Ghost]: http://github.com/tryghost/ghost/
[Ghost Casper]: https://github.com/moretwo/hexo-theme
