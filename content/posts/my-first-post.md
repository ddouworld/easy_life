---
title: "My firt time use hugo to build my website"
date: 2024-09-15T11:30:03+00:00
# weight: 1
# aliases: ["/first"]
tags: ["hugo", "hexo", "blog", "easyz", "bulid blog"]
author: "easyz"
showToc: true
TocOpen: false
draft: false
hidemeta: false
description: "Building the blog again, but using hugo"
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
---

### why choose the hugo to build my bolg

I've used hexo to build blogs before,it is very easy to build blog.and i can deploy it on github page.it not i need vps or other something that i must cost money.that's great.even thought i have a vps.but i dont use it.beause i think it's have many troble than bulid website on github page dirctly.it's just a simply website,so it's dont spend my many times.

### start bulid bolg by hugo

first,you should install the hugo.you can find the how to install hugo in they document(https://gohugo.io/documentation/)

emm,.it's similar hexo.you just know a few command and you can run a website in the browser.like

```
hugo
hugo server
hugo server -D
```

and the last but the most import command is

```
hugo help
```

### choose a theme and create new page by hugo

I use the [PaperMod](https://github.com/adityatelange/hugo-PaperMod/) theme ,it's veyy simply theme.you can use git clone the theme for your website.

```
git clone https://github.com/adityatelange/hugo-PaperMod themes/PaperMod --depth=1 theme
```

I use the git clone the theme project and put the PaperMod project in the theme folder.

```
hugo new my_first_post
```

use hugo command create a new conntent.

### other step

emm,I just wanted to briefly document this, and by the way, test the website display.Other deployment steps can be found in the documentation.You just need to Google it.
