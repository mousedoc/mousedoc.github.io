# mousedoc.github.io
For blog

### Deploy
When something is pushed to master, it is automatically distributed as a github action.

### Deploy on local
```
bundle exec jekyll serve
```

### Update style
```
cd mousedoc.github.io
npm install
gulp
```


### Template
```
---
layout: post
current: post
# cover: assets/images/water.jpg
navigation: True
title: Github Action에서 Unity Testrunner 돌리기
date: 2014-08-12 10:18:00
tags: github
class: post-template
subclass: 'post tag-github'
logo: assets/images/ghost.png
author: mousedoc
---

이것은 내용
```
