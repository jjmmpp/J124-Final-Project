# J124 Final Project - Salaries After Graduation
## Where does it pay off to focus your college efforts:
### School Type or Region or Major/Degree? 

I made some conclusions just looking at these data sets:

"School Type" is somewhat humorous, as a type of school is *party*. 

This data set was problematic because some schools were listed twice, in two categories, such as *state* and *party*. For purposes of writing an article, I would contact whoever put the data together for further information on what makes a school a "party school." I would want to include discussion of it because its interesting, but not without clarification from source of data. Further, I suspect most students will go to local schools for reasons of affordability. How many even have access to ivy league education? These are other reasons I did not analyze this data set. 

I found "Region" to be too limited in scope, without comparing it to the region one works in. I would want data on how region dependent are salaries before incorporating this data set. So, I did not analyze this data set.

The most useful analysis might be the result when considering **region residence when working** with **degree type**. That would provide knowledge to readers that they could actually use: *pick a good major, then the right region in which to find a job*. 

**I believe that the most valuable information from these data sets is *Degree Type**. That is **the** category in these data sets that allows for most freedom of choice -- not region or school type, as those options involve means and privilege.** This would be in my nutgraf, but first I would have to investigate this -- such as look into statistics on how close to home college students tend to stay when they go for higher education. 

## To begin: 

I evaluated by *starting salary*, *mid career salary* and *percent increase at mid-career*. The question to answer is:

### How much does one make at career start?
### How much does it go up from there? 

To get a full picture, it is important to look at highest and lowest. As a reader, I would want to see this information.

**Working in Excel**:
* I duplicated each data set and renamed my file WKG before original name. In case I inadvertently changed the data, I would have the original downloads.
  * I saved the original with ORG before name.  
* For each worksheet, to make sorting clearer, I deleted the top row. 
  * Then I froze the top and side panes.
  * I wrapped the text and expanded the row depth so I could read each column header easily.
* I added a “Percent change from Starting to Mid-Career Salary” colum and calculation to the School Type and Region sheets. 
  * I put in the formula
   * New number – original number/original number* or *=(D2-C2)/C2* for the first line.
 * Then double-clicked left corner to autofill to bottom.
 * I formatted the column to show numbers as percentages.

Next, to make pivot tables easier to deal with 
* I did a copy and paste special as values onto the “Percent change from Starting to Mid-Career Salary”  column to have the actual number in the cell instead of the formula. 

## Earnings by Majors
I started here, assuming this would be the most useful data to consider. 

### Which majors have the highest starting salaries?
*To solve, I made a pivot table of “Undergraduate Major” and “Starting Median Salary.” Then I sorted salary as descending to find top 5.*

![DegreeStartDesc](/Degree_Starting_Desc.jpg)

### Which majors have the lowest starting salaries?
*To solve, I made a pivot table of “Undergraduate Major” and “Starting Median Salary.” Then I sorted salary as ascending to find lowest 5.*

![DegreeStartAsc](/Degree_Starting_Asc.jpg)

### Which majors have the highest mid-career salaries? 
*To solve, I made a pivot table of “Undergraduate Major” and “Mid-Career Median Salary.” Then I sorted salary as descending to find top 5.*

![DegreeMidCareerAsc](/DegMidDesc.jpg)

### Which majors have the lowest mid-career salaries?
*To solve, I made a pivot table of “Undergraduate Major” and “Mid-Career Median Salary.” Then I sorted salary as ascending to find lowest 5.*

![DegreeMidCareerAsc](/DegMidAsc.jpg)

### Which majors have the highest % change from starting to mid-career salaries? 
*To solve, I made a pivot table of “Undergraduate Major” and “% change from Start to Mid.” Then I sorted salary as descending to find top 5.*

![Degree%Desc](/DegPerDesc.jpg)

### Which majors have the lowest % change from starting to mid-career salaries?
*To solve, I made a pivot table of “Undergraduate Major” and “% change from Start to Mid.” Then I sorted salary as ascending to find lowest 5.*

![Degree%Asc](/DegPerAsc.jpg)

Note: For my data visualization, I played with it in Google Sheets and uploaded the file here. Then I created a chart in XXXXX.

