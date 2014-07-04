Stem and leaf
========================================================

## Data

Sample of 19 exam grades randomly selected from a large class.

```r
grades <- c(76,74,82,96,66,76,78,72,52,68,86,84,62,76,78,92,82,74,88)
```

## Stem-and-leaf display

```r
stem(grades)
```

```
## 
##   The decimal point is 1 digit(s) to the right of the |
## 
##   5 | 2
##   6 | 268
##   7 | 24466688
##   8 | 22468
##   9 | 26
```


```r
stem(grades, scale = 2)
```

```
## 
##   The decimal point is 1 digit(s) to the right of the |
## 
##   5 | 2
##   5 | 
##   6 | 2
##   6 | 68
##   7 | 244
##   7 | 66688
##   8 | 224
##   8 | 68
##   9 | 2
##   9 | 6
```
