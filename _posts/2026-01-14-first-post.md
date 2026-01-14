---
title: "中国地图简单代码"
date: 2026-01-14
categories: [R]
tags: [cnmap, ggplot2]
layout: single
---

下面是最简代码：

```r
library(cnmap)
library(tidyverse)

getMap(subRegion = TRUE) %>%
  ggplot() +
  geom_sf() +
  theme_minimal()




[查看完整报告]({{ "/reports/2026-01-14-中国地图.html" | relative_url }})
