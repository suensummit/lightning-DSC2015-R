---
title       : R 資料分析上手課程 { Lightning Talk }
subtitle    : 2015 DSC 台灣資料科學愛好者年會
author      : Summit Suen
job         : Taiwan R User Group
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---
  
## Lightning Talk
  
![](https://t.kfs.io/upload_images/41788/DSC15_LOGO-___large.jpg)

--- .class #id 

## R <3 Baseball

---
  
## 工欲善其事，必先利其器
  

```r
install.packages("Lahman")
install.packages("Sxslt", repos = "http://www.omegahat.org/R", type = "source")
require(devtools)
install_github("openWAR", "beanumber")
```

---
  

```r
install.packages("httr")
install.packages("XML")
install.packages("stringr")
install.packages("CSS")
install.packages("rjson")
```
