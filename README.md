# LinkedIn-Dashboard

[Final Dashboard]( https://public.tableau.com/app/profile/tim8067/viz/LinkenInDashboard/Dashboard1?publish=yes)

[Dataset]( https://github.com/jldbc/coffee-quality-database/blob/master/data/arabica_data_cleaned.csv) <br>


## Summary
* **998** total coffee bean samples **25 countries** 
* **82.69** average overall Q score per sample
* Our findings:
   * Mexico highest coffee bean sample amount submitted **225**

   * Washed/Wet most popular Processing Method **73%**

   * **5** countries (Mexico, Guatemala, Colombia, Brazil, Taiwan) that contribute to **68%** of total sample size


## Code and Resources Used 
**JupyterLab:** 3.3.3 <br>
**Python within JupyterLab:** 3 <br>
**Packages:** pandas, numpy, matplotlib, seaborn, sklearn <br>
**RStudio:** 2022.07.0 <br>
**Packages:** dplyr, tidyr, rcompanion, car, ggplot2, tidyverse, mvnormtest, writexl <br>
**Articles:** 
   - [Two-way Anova] (https://www.statology.org/two-way-anova-r/)

## Data Wrangling
We initially looked at our basic column structures and what columns we wanted to keep.
Once we had the columns we wanted to work with, we removed the null values.


We then switched to looking at our columns data types to get a good understanding of what possible changes we may need to make for our statistical modeling. Here is the recoding we performed:

* Recoded the following Columns from strings to integers
    * Country.of.Origin
    * Processing.Method
* Created a new Column, Region, breaking the countries into 5 regions
    * Initially there were 4 regions; Africa, Central America, Asia and South America
    * The 4 regions were skewed since Mexico made Central America disproportionate, so Mexico became its own region
    * Also recoded Region from string to integer

For each of the variables above, they were categorical data. We changed them for this reason:
1. We wanted to run a Correlation Matrix 
<img style="display: inline; margin: 0 5px;" title="Correlation Matrix" src="img/corrMatrix.png" alt="" width="800" height="300"/>
   
