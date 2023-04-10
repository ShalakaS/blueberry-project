# Why Are We Talking About Blueberries From Peru?

* This is a Data Studio class project.
* The prompt for this project was to build narrative using graphics.

### What I Aimed to Accomplish
The aim of this project was to analyse data about world food production to find out how crops were performing world-wide. The data used includes harvest area and production of primary crops between 2012 and 2021 from United Nations Food and Agriculture Organization (UNFAO). 

### Findings
I first filtered the data for production and grouped it by year, number of producer countries, and then by sum of production to find the fastest growing crop. I found blueberry to be the fastest growing crop with 131% increase in production in 2021 compared to 2012 and a massive spurt in the harvest land: production ratio.

### Data Collection Process

The data was collected directly from UNFAO's UNSTAT platform. The shape files for the map were taken from Massachusetts Institute of Technology's GeoWeb platform. The information about the Peru/Humboldt current was from Fresh Fruit Portal's news report (https://www.freshfruitportal.com/news/2013/05/03/geography-to-play-key-role-in-perus-blueberry-sector/). 

Source: FAOSTAT (https://www.fao.org/faostat/en/#home) | MIT GeoWeb (https://geodata.mit.edu/?f%5Bdc_format_s%5D%5B%5D=Shapefile&f%5Bdct_spatial_sm%5D%5B%5D=Peru) 

### Overview of the Data Analysis Process

Initial finding was of avocado but I realised, rather late, that 27 new countries have recorded their avocado production but out of them, 21 had recorded the production as 0.00 tonne. After accounting for null values, I found that group of other pome fruits and a group of anise, cumin, coriander seeds were the top two producers. But the source of the data cited lack of data as the reason for this grouping. Therefore, I made the editorial decision to not count them in the data. After that, blueberries topped the list of percent change in production from 2012 to 2021.

### New Skills and Lessons Learned

* I have been keeping a personal list of things I must do immediately after collection of data. I learned a very important lesson and made an addition to my list: always check for null values even in columns that you are not using.
* I learned to add pictures to the spheres in a scatter plot in ggplot.

### Future of This Project

I tried to explain the Peru current phenomenon but could not do it in detail for two reasons:
1. I ran out of time. 
2. I did not know how to create the effect of an ocean current in freehand.

I also tried to make a waffle chart to show the ratio of harvest land to production and explain why the ratio had gone down in 2021 even though, in raw numbers, production had increased a lot. At a later date, I would like to deep dive into it as it is an interesting topic that covers environment, labour, and climate change.
