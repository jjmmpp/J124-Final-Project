# J124 Final Project - Salaries After Graduation
## Where does it pay off to focus your college efforts:
### Major/Degree
### School Type
### Region

I wanted to see if from this data it could be determined which education choices were the best and which were the worst for earning potential. 

One data set is humorous - describing a type of school as *party*. Since I included this data set, I thought my article pitch should be on the more levitous side. This data set was also problematic because some schools had two categories, such as *state* and *party*. For purposes of writing an article, I would contact whoever put the data together for further information on what makes a school a "party school." 

Also, I question how useful is this data beyond interest/amusement? Most will go to local schools for reasons of affordability. Further, how many even have access to ivy league education? That would be important to include in the article.

**I believe that the most valuable information from these data sets is *Degree*. That is what one can category in these data sets that allows for most freedom of choice -- not region or school type.** This would be in my nutgraf. I would have to investigate this further -- such as look into statistics on how close to home college students tend to stay 

What would be further explored in my article -- beyond this data set -- is how region dependent are salaries? I mean region you work in after graduation not where the college was. Where you live when you work may matter more than all the other choices regrading college in the data set. That would be interesting to see. Or, what is the result when combining region residence with degree type.  

##To being: 

I evaluated by *starting salary* and *percent increase at mid-career*. The question to answer is:

###How much do you make at career start?
###How much does it go up from there. 

I thought that to get a full picture, it was important to look at highest and lowest. As a reader, I would want to see this information, no matter the focus of the article. 

**Working in Excel**:
* I duplicated each data set and renamed my file WKG before original name. In case I inadvertently changed the data, I would have the original downloads.
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

### Which majors have the highest % change from starting to mid-career salaries? 
*To solve, I made a pivot table of “Undergraduate Major” and “% change from Start to Mid.” Then I sorted salary as descending to find top 5.*

![Degree%Desc](/DegPerDesc.jpg)

### Which majors have the lowest % change from starting to mid-career salaries?
*To solve, I made a pivot table of “Undergraduate Major” and “% change from Start to Mid.” Then I sorted salary as ascending to find lowest 5.*

![Degree%Asc](/DegPerAsc.jpg)


