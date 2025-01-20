+++
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = '{{ .Date }}'
lastMod = '{{ .Date }}'
categories = ['分类1']
tags = ['标签1']
summary = ""
# 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
# weight = 1 
+++

此处内容将会出现在摘要（summary）里

<!--more--> 

此处开始为正文