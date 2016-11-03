## R Tutorial

This presentation is a basic to intermediate tutorial on the use of R (base R only). Base R is the R software without any external packages.

The presentation has been written with `rmarkdown`, `knitr` and `tableHTML` in RStudio using the ios slides format.

It follows the structure of [Hadley's Advanced-R book](http://adv-r.had.co.nz/) and contains information based on the following topics:

* Data Types
* Data Structures
* Subsetting
* Vocabulary
* Functions
* Important Functions*
* Case Study

*(this is not part of Hadley's book but I feel it is really necessary for beginners to know how to use these functions)

## View on browser

To view the presentation on your browser you can do:

```
#create a temp file
temp_file_location <- tempfile('presentation_r', fileext = '.html')

#download the r presentation
download.file('https://raw.githubusercontent.com/LyzandeR/R-tutorial/master/R-Tutorial.html', temp_file_location)

#view it on browser
browseURL(temp_file_location)
```