---
title       : NOAA-based Weather Event Viz
subtitle    : A Shiny App for visualizing impacts of severe weather events
author      : Sabank
job         : Course Project - Developing Data Products - Coursera - Dec 27, 2015
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introdution

The basic purpose of this 'Developing Data Products' course project is to demonstrate the ability to deploy a 'Shiny' app on the Web and to pitch it through a 'Slidify' presentation.

The Shiny App allows the user to explore the National Oceanic and Atmospheric Administration's (NOAA) [Storm Database](https://www.ncdc.noaa.gov/stormevents/) and to visualize some basic information about the impacts from severe weather events in the United States between the years 1950 and 2011.

In particular, the visualizer offers, through a combination of dynamic 'motion' charts, an interactive way to exploring several indicators over time.

--- .class #id 

## NOAA-based Weather Event Visualizer

Launch the App [here](https://sabank.shinyapps.io/DevelopingDataProducts)

Functionalities:

1. three motion charts available (bubble, bar, line) in reference to the [Google Chart Tools](https://developers.google.com/chart/terms)
2. options to customize viewer's experience
3. select input/output among variables (Fatalities, Occurrence, Time, State)

```
##   STATE Year Fatalities Occurrence
## 1    AL 1950         15          2
## 2    AR 1950         51         13
## 3    CO 1950          1          3
## 4    CT 1950          3          2
## 5    FL 1950          0          6
## 6    GA 1950          1          4
```

--- .class #id

## Data

Download the file [here](https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2FStormData.csv.bz2)

The file was specifically processed for the needs of this project.

The focus was to provide with quantitative information for the google-based plot.

Therefore, data was reshaped to quantify fatalities (FATALITIES + INJURIES) and number of occurence of events (EVTYPE) by state (STATE)

Access the GitHub Repo [here](https://github.com/sabank/DevelopingDataProducts.git)

--- .class #id

## Resources

Coursera - Developing Data Products:
https://www.coursera.org/learn/data-products

Shiny app deployment:
https://www.shinyapps.io/ 

GitHub:
https://github.com/

Google Visualization API:
https://developers.google.com/chart/
