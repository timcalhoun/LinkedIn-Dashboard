# LinkedIn-Dashboard

[Final Dashboard]( https://public.tableau.com/app/profile/tim8067/viz/LinkenInDashboard/Dashboard1?publish=yes)

[Dataset]( https://github.com/timcalhoun/LinkedIn-Dashboard/tree/main/Datasets) <br>


## Summary
* Created a dashboard from my LinkedIn connections and message data
* My findings:
   * In about 3 months time when I really started using LinkedIn, my connections grew 100

   * I don't use LinkedIn messaging much, maybe there is room for improvement of networking here

   * My current employer has the most connections


## Software and Resources Used 
**Tableau Desktop:** 2022.3.0 <br>
**Microsoft Office - Excel:** 2021 <br>
**Articles:** 
   - [Tableau Dashboard - Avery Smith] (https://www.youtube.com/watch?v=vsX0GxmW7gg)
   - [Excel - How to extract first letter of each word from cell?] (https://www.extendoffice.com/documents/excel/1580-excel-extract-first-letter-of-each-word.html)

## LinkedIn Data
You have access to all your data within LinkedIn, you just need to request it, which takes about 24 hours
* Go to Settings & Privacy under you name drop-down, select Data Privacy
  * Next select Get a copy of your data
    * Select Download larger data archive, including connections, contacts, account history, and information we infer about you based on your profile and activity.
      * Request Archive (and wait about 24 hours for complete data)
<img style="display: inline; margin: 0 5px;" title="LinkedIn Data Retrieval" src="img/LinkedIn Data Retreival.png" alt="" width="800" height="300"/>

We then switched to looking at our columns data types to get a good understanding of what possible changes we may need to make for our statistical modeling. Here is the recoding we performed:

* Recoded the following Columns from strings to integers
    * Country.of.Origin
    * Processing.Method
* Created a new Column, Region, breaking the countries into 5 regions
    * Initially there were 4 regions; Africa, Central America, Asia and South America
    * The 4 regions were skewed since Mexico made Central America disproportionate, so Mexico became its own region
    * Also recoded Region from string to integer


