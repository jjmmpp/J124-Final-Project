# J124 Final Project - Salaries After Graduation
## Where does it pay off to focus your college efforts:
### Major/Degree
### School Type
### Region

I wanted to see if from this data it could be determined which education choices were the best and which were the worst for earning potential. 

One data set is humorous - describing a type of school as "party". Since I included this data set, I thought my article pitch should be on the more levitous side.

Also, I question how useful is this data beyond interest/amusement? Most kids will go to local schools for affordability. How many have access to ivy league education? That would be important to include in the article.

**The most valuable information from these data sets is *Degree*. That is what one can actually choose, no matter region or school type.** This would be in my nutgraf.

What would be further explored in my article -- beyond this data set -- is how region dependent are salaries? That may matter more than all the other choices regrading college in the data set.

I evaluated by *starting salary* and *percent increase at mid-career*. 

I thought that to get a full picture, it was important to look at highest and lowest. I also thought that as a reader, I would want to see this information, no matter the focus of the article. 

Working in Excel:
* I duplicated each data set and renamed it WKG before original name so that in case I inadvertently changed the data, I would have the original downloads.
* For each worksheet, to make sorting clearer, I deleted the top row. 
  * Then I froze the top and side panes.
  * I wrapped the text and expanded the row depth so I could read each column header easily.
* I added a “Percent change from Starting to Mid-Career Salary” colum and calculation to the School Type and Region sheets. 
  * I put in the formula
  * New number – original number/original number* or *=(D2-C2)/C2* for the first line.
* Then double-clicked left corner to autofill to bottom.
* I formatted the column to show numbers as percentages.

Next, to make pivot tables easier to deal with 
* I did a copy and paste special as values onto that column to have the actual number in the cell instead of the formula. 

## Earnings by Majors

### Which majors have the highest starting salaries?
*To solve, I made a pivot table of “Undergraduate Major” and “Starting Median Salary.” Then I sorted salary as descending to find top 5.*

![DegreeStartDesc](/Degree_Starting_Desc.jpg)

### Which majors have the lowest starting salaries?
*To solve, I made a pivot table of “Undergraduate Major” and “Starting Median Salary.” Then I sorted salary as ascending to find lowest 5.*

![DegreeStartAsc](/Degree_Starting_Asc.jpg)

To solve, I made a pivot table of “Undergraduate Major” and “Mid-Career Median Salary.” Then I sorted salary as descending

3 - Which majors have the highest mid-career salaries? 

To solve, I made a pivot table of “Undergraduate Major” and “Mid-Career Median Salary.” Then I sorted salary as ascending

4 - Which majors have the lowest mid-career salaries?

To solve, I made a pivot table of “Undergraduate Major” and “% change from Start to Mid.” Then I sorted salary as descending.

5 - Which majors have the highest % change from starting to mid-career salaries?

To solve, I made a pivot table of “Undergraduate Major” and “% change from Start to Mid.” Then I sorted salary as ascending.

6 - Which majors have the lowest % change from starting to mid-career salaries?


