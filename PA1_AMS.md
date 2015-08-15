# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data


```r
dataset <- read.csv("activity.csv", header=T, sep=",", na.strings="?")
str(dataset)
```

```
## 'data.frame':	17568 obs. of  3 variables:
##  $ steps   : Factor w/ 618 levels "0","1","10","100",..: 618 618 618 618 618 618 618 618 618 618 ...
##  $ date    : Factor w/ 61 levels "2012-10-01","2012-10-02",..: 1 1 1 1 1 1 1 1 1 1 ...
##  $ interval: int  0 5 10 15 20 25 30 35 40 45 ...
```



## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
