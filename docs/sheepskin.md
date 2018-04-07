
---
output: html_document
editor_options: 
  chunk_output_type: console
---
# Sheepskin and Returns to Schooling

This replicates Figures 6.3 and 6.4 of *Mastering 'Metrics*.
These analyses use a fuzzy RD design to analyze the “sheepskin effects” of a high school diploma [@ClarkMartorell2014].


```r
library("tidyverse")
```

Load `sheepskin` data.

```r
data("sheepskin", package = "masteringmetrics")
```


## References {-}

-   <http://masteringmetrics.com/wp-content/uploads/2015/02/ReadMe_Sheepskin.txt>
-   <http://masteringmetrics.com/wp-content/uploads/2015/02/cm_graphs.do>
