```R
myColorPalette <- tidyr::replace_na(scales::gradient_n_pal(c('lightgrey', '#e8e72c', '#c50000', '#c50000'), values = c(0.1, 0.4, 0.8, 1))(seq(from = 0, to = 1, length.out = 100)), 'lightgray')
```
