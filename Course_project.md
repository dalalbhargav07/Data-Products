Developing Data Products Project: How to select a car for your trip
========================================================
author: Bhargav Dalal 
date: "September 24, 2016"
autosize: true


Introduction
========================================================


This is a part of the Course Project for Developing Data Products class from Coursera. We need ro first create a Shiny application and deploy it on Rstudio's servers. Then use Rstudio Presenter to prepare a presentation about the application we created above. So this is the second part of the course project.

The app developed for the first part of the assignment is avalilable at:

https://dalalbhargav07.shinyapps.io/carzz/

Source code for ui.R and server.R files are available on the GitHub:

https://github.com/dalalbhargav07/Data-Products


Select your car for a trip App
========================================================

with the mtcars dataset from [R], this app will find you the perfect car for your trip by following steps.

- Inform the distance of your trip and the price of gasoline in your region. These information will be used to calculate the Gasoline Expenditure for each car in the dataset. 
- Enter the maximum amount of money you want to spend on gasoline, and the table shows only the cars that have Miles per Gallon (mpg) that can go below this value.
- Choose some caractheristcs of the cars that you desire: Cylinders, Horse Power and Transmission. 


Dataset
========================================================

The Motor Trend Car Road Tests (mtcars) dataset was extracted from the 1974 Motor Trend US magazine, and comprises fuel consumption and 10 aspects of automobile design and performance for 32 automobiles (1973-74 models). Here are some carachteristics of the data:


```
                   mpg cyl disp  hp drat    wt  qsec vs am gear carb
Mazda RX4         21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
Mazda RX4 Wag     21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
Datsun 710        22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
Hornet 4 Drive    21.4   6  258 110 3.08 3.215 19.44  1  0    3    1
Hornet Sportabout 18.7   8  360 175 3.15 3.440 17.02  0  0    3    2
Valiant           18.1   6  225 105 2.76 3.460 20.22  1  0    3    1
```

Plots
========================================================

Here are some simple relationship between miles per gallon (mpg) and weight (wt).

![plot of chunk unnamed-chunk-2](Course_project-figure/unnamed-chunk-2-1.png)

