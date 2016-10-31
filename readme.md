## R Tutorial

A basic to intermediate R tutorial slides.

## View on browser

To view the presentation on your browser you can do:

```
#create a temp file
temp_file <- tempfile('test', fileext = '.html')

#download the r presentation
download.file('https://raw.githubusercontent.com/LyzandeR/R-tutorial/master/R-Tutorial.html', temp_file)

#view it on browser
browseURL(a)
```