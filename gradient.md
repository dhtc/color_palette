```R
myColorPalette <- tidyr::replace_na(scales::gradient_n_pal(c('lightgrey', '#e8e72c', '#c50000', '#c50000'), values = c(0.1, 0.4, 0.8, 1))(seq(from = 0, to = 1, length.out = 100)), 'lightgray')
```

```R
# grey - red
scale_color_gradientn(colors = c('#d9d9d9', '#FFF5F4', '#CD2626'))
```

```R
# grey - red
color_map_dict = list(colors = c('#babab7',
 '#bbbbb5', '#bbbbb4', '#bcbcb2', '#bcbcb1', '#bdbdaf', '#bdbdae', '#bebeac', '#bebeaa', '#bfbfa9', '#bfbfa7', '#c0c0a6', '#c0c0a4', '#c1c1a3', '#c1c1a1',
 '#c2c29f', '#c2c29e', '#c3c39c', '#c3c39b', '#c4c499', '#c4c498', '#c5c596', '#c5c594', '#c6c693', '#c6c691', '#c7c790', '#c8c78e', '#c8c88d', '#c9c88b',
 '#c9c98a', '#cac988', '#caca86', '#cbca85', '#cbcb83', '#cccb82', '#cccc80', '#cdcc7f', '#cdcd7d', '#cecd7b', '#cece7a', '#cfce78', '#cfcf77', '#d0cf75',
 '#d0d074', '#d1d072', '#d1d170', '#d2d16f', '#d2d26d', '#d3d26c', '#d3d36a', '#d4d369', '#d4d467', '#d5d565', '#d6d564', '#d6d662', '#d7d661', '#d7d75f',
 '#d8d75e', '#d8d85c', '#d9d85a', '#d9d959', '#dad957', '#dada56', '#dbda54', '#dbdb53', '#dcdb51', '#dcdc4f', '#dddc4e', '#dddd4c', '#dedd4b', '#dede49',
 '#dfde48', '#dfdf46', '#e0df44', '#e0e043', '#e1e041', '#e1e140', '#e2e13e', '#e3e23d', '#e3e23b', '#e4e33a', '#e4e338', '#e5e436', '#e5e435', '#e6e533',
 '#e6e532', '#e7e630', '#e7e62f', '#e8e72d', '#e8e72b', '#e9e82a', '#e9e828', '#eae927', '#eae925', '#ebea24', '#ebea22', '#eceb20', '#eceb1f', '#edec1d',
 '#edec1c', '#eeed1a', '#eeed19', '#efee17', '#efea17', '#efe618', '#efe218', '#efdd18', '#efd918', '#efd519', '#efd119', '#efcd19', '#eec919', '#eec51a',
 '#eec01a', '#eebc1a', '#eeb81a', '#eeb41b', '#eeb01b', '#eeac1b', '#eea81b', '#eea41c', '#ee9f1c', '#ee9b1c', '#ee971c', '#ee931d', '#ee8f1d', '#ee8b1d',
 '#ee871d', '#ed821e', '#ed7e1e', '#ed7a1e', '#ed761e', '#ed721f', '#ed6e1f', '#ed6a1f', '#ed651f', '#ed6120', '#ed5d20', '#ed5920', '#ed5520', '#ed5121',
 '#ed4d21', '#ed4921', '#ed4421', '#ed4022', '#ec3c22', '#ec3822', '#ec3422', '#ec3023', '#ec2c23', '#ec2723', '#ec2323', '#ec1f24', '#ec1b24', '#eb1b24',
 '#ea1b24', '#e91b24', '#e81b24', '#e71b24', '#e61b24', '#e51b23', '#e41b23', '#e31b23', '#e21b23', '#e11b23', '#e01b23', '#df1a23', '#de1a23', '#dd1a23',
 '#dc1a23', '#db1a23', '#da1a23', '#d91a23', '#d81a22', '#d71a22', '#d61a22', '#d51a22', '#d41a22', '#d31a22', '#d21a22', '#d11a22', '#d01a22', '#cf1a22',
 '#ce1a22', '#cd1a22', '#cc1a21', '#cb1a21', '#ca1a21', '#c91a21', '#c81a21', '#c71a21', '#c61a21', '#c51921', '#c41921', '#c31921', '#c21921', '#c11921',
 '#c01921', '#bf1920', '#be1920', '#bd1920', '#bc1920', '#bb1920', '#ba1920', '#ba1920', '#b91920', '#b81920', '#b71920', '#b61920', '#b51920', '#b41920',
 '#b3191f', '#b2191f', '#b1191f', '#b0191f', '#af191f', '#ae191f', '#ad181f', '#ac181f', '#ab181f', '#aa181f', '#a9181f', '#a8181f', '#a7181f', '#a6181e',
 '#a5181e', '#a4181e', '#a3181e', '#a2181e', '#a1181e', '#a0181e', '#9f181e', '#9e181e', '#9d181e', '#9c181e', '#9b181e', '#9a181d', '#99181d', '#98181d',
 '#97181d', '#96181d', '#95181d', '#94181d', '#93171d', '#92171d', '#91171d', '#90171d','#8f171d', '#8e171d', '#8d171c', '#8c171c', '#8b171c', '#8a171c',
 '#89171c', '#88171c', '#87171c'),
                     values = 1:256/256)
scale_color_gradientn(colours = color_map_dict$colors, values = color_map_dict$values, na.value = 'lightgrey')                     
```

```R
# grey - darkred
scale_color_gradientn(colours = colorRampPalette(c('#d9d9d9', '#A50F15', '#67000D'))(9), guide = guide_colorbar(label = F))
```
