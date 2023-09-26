---
title: 20230926 | I can use github and vscode simply now
author: Qing
date: '2023-09-26'
slug: 20230926-i-can-use-github-and-vscode-simply-now
categories:
  - Github Project
  - Python Project
tags:
  - Github Project
  - Python Project
---

Recently, my Python course has finished. Although it was an introductory course, teacher provided insightful explanations, guided us through **the learning path**, and offered **interactive learning materials**(such as .ipynb notebooks). I am very satisfied with it and have learned a lot.

Today, I finally managed to use Python and GitHub projects. I utilized the project at [weibo-crawler](https://github.com/dataabc/weibo-crawler) and successfully retrieved Weibo records for 迪丽热巴. It was the project's default setting and I'm not her fan 😊.

Learning bit by bit\~⛳


```r
# 加载rio包
library(rio)


# 读取文件
data <- import("D:/career/data/weibo-crawler-master/weibo/Dear-迪丽热巴/1669879400.csv", encoding = "UTF-8")



print(data)
```

```
##   4950274110652708\t Nl5Rh2JNy
## 1   4946642358768224 NjznBAN0Y
## 2   4944935696730327 NiQYVseRF
##   期待本次#迪奥二零二四春夏成衣系列发布秀#，快与我一同在这艺术视觉盛宴中探索优雅摩登的女性精神吧。@DIOR迪奥
## 1                                                             跟生活合影tips第二弹，继续get点滴快乐[我来了]
## 2                                                                           大美女幂姐@杨幂 生日快乐哇～\n 
##   V4
## 1 NA
## 2 NA
##                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       https://wx3.sinaimg.cn/large/001P0DUIgy1hia468ttuoj63hc4n4x6s02.jpg
## 1 https://wx2.sinaimg.cn/large/001P0DUIly1hhyj44ro3lj61jk2bc7wh02.jpg,https://wx3.sinaimg.cn/large/001P0DUIly1hhyj475753j61ys2txe8202.jpg,https://wx3.sinaimg.cn/large/001P0DUIly1hhyj4am2vhj62e6372hdv02.jpg,https://wx2.sinaimg.cn/large/001P0DUIly1hhyj4e2hunj626v3407wk02.jpg,https://wx4.sinaimg.cn/large/001P0DUIly1hhyj4kqmxwj62c0340e8302.jpg,https://wx3.sinaimg.cn/large/001P0DUIly1hhyj4hegw6j624a2vce8302.jpg,https://wx4.sinaimg.cn/large/001P0DUIly1hhyj4mw2nmj61xs2mj4qq02.jpg,https://wx4.sinaimg.cn/large/001P0DUIly1hhyj4nr0l6j60u015ftrv02.jpg,https://wx2.sinaimg.cn/large/001P0DUIly1hhyj43h548j61c921znpd02.jpg,https://wx1.sinaimg.cn/large/001P0DUIly1hhyj4q8oubj626p2zgnpe02.jpg
## 2                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     https://wx2.sinaimg.cn/large/001P0DUIly1hht34hq6ifj62p841uqv502.jpg
##   V6 V7 2023-09-26T17:33:01 V9  471923   40764  153798
## 1 NA NA 2023-09-16 17:01:45 NA 5028437 1000000 1000000
## 2 NA NA 2023-09-12 00:00:05 NA 1175030   58753   13480
##   迪奥二零二四春夏成衣系列发布秀 DIOR迪奥 2023-09-26 17:33:01
## 1                             NA          2023-09-16 17:01:45
## 2                             NA     杨幂 2023-09-12 00:00:05
```

  
   
  
  
    


![迪丽热巴](images/20230912T_4944935696730327.jpg "img")
