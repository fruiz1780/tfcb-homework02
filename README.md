---
title: "README.md"
output: 
  md_document:
    variant: markdown_github
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

Create a file called README.md and populate with Markdown. Demonstrate headers, lists, links, embedded images (by linking to images contained in the directory) and tables in this readme.


# This is a big header
## Another header that is smaller
### A third level of headers, even smaller header



So I am making a bulleted list:
* Data:
  * ! [Survey data](data/Survey_Data.xlsx)
* Images:
  * ! [Rhytidoponera metallic](images/casent-0172345_Rhytidoponera_metallica.jpg)
  * ! [Camponotus darwinii](images/casent-0191696_Camponotus_darwinii.jpg)
  * ! [Acanthomyrmex ferox](images/casent-0901788_p-1-high_Acanthomyrmex_ferox.jpg)
  * ! [Cataglyphis fortis](/casent-0906296_p-1-high_Cataglyphis_fortis.jpg)
  
This can be further viewed on my Github repository for [tfcb-homework02](https://github.com/fruiz1780/tfcb-homework02)



A table demonstration:
Date collected  | Species  | Weight
------------- | ------------- | -------------
2020/04/20  | Cataglyphis fortis  | 2
2020/05/20  | Camponotus darwinii  | 4


I looked at the website that Trevor Bedford recommended for markdown help. Specifically, for how to link images and files in the markdown file: <https://r4ds.had.co.nz/r-markdown.html>.
