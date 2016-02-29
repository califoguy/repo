Dataset Viewer and Sampler Presentation
========================================================
author: Anand
date: 27-FEB-2016



Brief Summary
========================================================

> - This is part of the coursera project. 
> - The objective is to present the features of the 
Shiny application .
> - To highlight the application components and some code.



Components of the Application - Part I
========================================================

> - The App consists of a ui.R and the server.R files. The 
application highlights the following features.

> - The libaries used are shiny and datasets.

> - The Server.R uses ShinyServer function to perform Input Output actions.

> - The ui.R uses the ShinyUI function and interacts with the server.R file.

Components of the Application - Part II
========================================================

The ui.R provides the following capabilities:
> - A Listbox control listing datasets to choose from.
> - The number of observations to view from each dataset (defaulting to 10).
> - The Summary of each data set and a table view for 
  viewing the data on the Main Panel.
> - The datasets included in the application are 
  sleep, WorldPhones, rock, pressure, cars, Indometh

Code - Summary of cars data and plot
========================================================


```r
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```
***
![plot of chunk unnamed-chunk-2](DatasetSamplerPresentation-figure/unnamed-chunk-2-1.png)
