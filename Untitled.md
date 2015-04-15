# My Analysis
Niels Hanson  
April 15, 2015  

# Preamble

* load required librareis


```r
# install.packages("GGally")
library("GGally")
```

```
## Warning: package 'GGally' was built under R version 3.1.2
```

* Load the HOT metadata from a tab-separate value file:


```r
hot_metadata <- read.table("data/HOT_METADATA2.txt", header=T, row.names=1, sep = "\t")
```


*




