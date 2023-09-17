---
title: 230917 | Presentation of English speaking class
author: Qing
date: '2023-09-17'
slug: 230917-presentation-of-english-speaking-class
categories:
  - R Project
tags:
  - R Project
---




```r
library(ggplot2)
```




```r
# 创建数据框
data <- data.frame(
  Year = c(1980:2019),
  Publications = c(2, 4, 6, 9, 6, 4, 8, 7, 42, 28, 25, 36, 36, 42, 49, 56, 48, 47, 43, 58, 60, 58, 77, 91, 91, 115, 132, 138, 150, 122, 124, 163, 179, 150, 124, 122, 124, 120, 71, 99)
)

# 创建趋势图
ggplot(data, aes(x = Year, y = Publications)) +
  geom_line() +           # 添加折线图层
  geom_point() +          # 添加点图层
  labs(title = "Literature Trends on the Topic of Euthanasia in China", x = "Year", y = "Number of Publications") +  # 添加标题和轴标签
  theme_minimal()         # 使用简约主题
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-2-1.png" width="672" />

