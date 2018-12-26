

# Data Documentation: 

One bigger issue was the different nameing convention of the World Bank and the GHO. 
We prepared the data so that we used the GHO naming convention and also only the Countries where we got Life Expecatancy data from the WHO. 
Also sometimes it is not clear what is part of a Country. Are the islands of UK and Netherlands also part of the GHO data, because in the World Bank data it is seperate. 
There is no information on the WHO site on what is part of this country. 

The Research and development expenditure has a lot of missing values. This need to inspected further if this data is usefull. 

In the case of 'Serbia and Montenegro (former)' which split up in 2006 we jsut have data until 2005 and after data we have data for Serbia and Montenegro.

The country Rwanda contained two values per colunm for Life Expactancy. As a comment in the dataset set it said 'High HIV countries' on the second value. We just choose the first value to use. 

One has to keep in mind that most of the data we are dealing here are estimates! 
For example the a report on how to estimate Life Expectancy can be found here https://www.who.int/healthinfo/statistics/LT_method.pdf



## Learned Lesson: 

Try to find all data you want from the same source. For example Life expectancy would also be available at WorldBank, which would be much easier to combine with the other data then. Also try to all export the data in one file, so you can process it easier later. 

