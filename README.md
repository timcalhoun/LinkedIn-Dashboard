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

## Excel
To protect the privacy of whom I was messaging, I wanted to grab the first initial of first and last name, versus displaying full name
* I Googled a how to grab first letter and quick way to add this function to Excel and updated messages csv
 
<img style="display: inline; margin: 0 5px;" title="Excel - First & Last name initials" src="img/Excel function.png" alt="" width="800" height="300"/>

## Tableau Desktop
To pull data into Tableau, under Connect, select file type you are bringing in, for this instance it is a Text file (csv)
* From the Connections drop-down select New Data Source and you can bring in your other csv files
  * From there start building your separte worksheets, till you have what you need to put your dashboard together
  * Click on New Dashboard tab next to the New Worksheet tab and you will see your built worksheets to drag and drop
    * You will want to make sure you select Floating under the Objects pane so you can place the worksheets where you want in the dashboard
    * Finally Save As to publish to Tableau Public

<img style="display: inline; margin: 0 5px;" title="Excel - First & Last name initials" src="img/LinkedIn Dashboard.png" alt="" width="800" height="300"/>

