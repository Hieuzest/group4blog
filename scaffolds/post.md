---
title: {{ title }}
date: {{ date }}
tags:
categories:
---


<div id="container"></div>
<link rel="stylesheet" href="https://imsun.github.io/gitment/style/default.css">
<script src="https://imsun.github.io/gitment/dist/gitment.browser.js"></script>
<script>
  var gitment = new Gitment({
    id: 'location.href', // 可选。默认为 location.href
    owner: '16983883', // 可以是你的GitHub用户名，也可以是github id
    repo: 'group4blog',
    oauth: {
      client_id: 'b53b0376640bfdfd489f',
      client_secret: '773c9215d96ed67d305be40b22b623b9a393d1a3',
    },
  })
  gitment.render('container')
</script>