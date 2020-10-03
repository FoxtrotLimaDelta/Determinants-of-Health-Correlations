# Determinants-of-Health-Correlations
D3-Challenge - Journalism Data Visualization

Correlations between the Determinants of Health 

 The challenge was to use both html and Javascript to pull in data, we used the provided data from the US Census Bureau and the Behavioral Risk Factors Surveillance System in a csv file. No scrubbing of data was necessary for this challenge. Adjustments were necessary to ensure the html, d3style.css, and the app.js could talk with each other. This meant making sure we matched variable names across all code. 

We set the shape, size, margins, etc. of the svg. Then wrote code for the scatter plot and to append data to the chartGroup. Using D3 we read in the csv file before parsing the data and casting it as numbers. We parsed more data than we used as the next step would be to enable the user to select different data points and see the relationship of each to the rest of the determinants of health. The axis functions will be a challenge during that next step and for now is only coded to the first data point options. We still need to add functions request and receive user input, to switch data based on that input; likely providing a dropdown box. The Axis labels will need the same updating of data base on user input. 

We adjusted the chart area to spread out the bubbles as shrinking the scale of the bubbles made them smaller than seemed visually appealing. There are still a few pairs that overlap: Wyoming and Alaska have the exact same poverty rate, Missouri and Montana poverty rate differs by only .1 percentage points, same hold true for Arizona and Tennessee, while Virginia and Colorado differ by .4, lastly, North Dakota and Hawaii barely overlap on the edges and they only differ by .1.

Getting the state abbreviations into the circles proved an interesting challenge. The ability to make all of them visible required an unexpected change to the code. Once changed all of the state abbreviations became visible, however, the tool tips then required one to click on the edge of the circle as opposed to the center where the abbreviations now reside. A combination of d3style.css and inline spacing adjustment centered the abbreviations in each circle.

It has been a fun project so far and the next steps promise to be even more challenging!
