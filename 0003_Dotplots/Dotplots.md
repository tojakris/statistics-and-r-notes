Dotplots
========================================================

## Data

Sample of 19 exam grades randomly selected from a large class.

```r
grades <- c(76,74,82,96,66,76,78,72,52,68,86,84,62,76,78,92,82,74,88)
class.grades <- data.frame(grades = grades)
```

## Dotplot

```r
library(ggplot2)

ggplot(class.grades, aes(x = grades)) + 
    geom_dotplot(binwidth = 1.5, 
                 stackratio = 1.7, 
                 dotsize = 0.75,
                 fill="palegreen3") +
    labs(title="19 Exam Scores") +
    theme(plot.title = element_text(lineheight=.8, face="bold")) +
    xlab("Score") +
    scale_y_continuous(name = "Frequency", breaks = NULL)
```

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2.png) 
