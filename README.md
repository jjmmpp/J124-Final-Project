# J124 Final Project - Salaries After Graduation
## Where does it pay off to focus your college efforts:
### School Type or Region or Major/Degree?  

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
* I added a “Percent change from Starting to Mid-Career Salary” column and calculation to the School Type and Region sheets, which did not have that already.
  * I put in the formula: *New number – original number/original number* or *=(D2-C2)/C2* for the first line.
  * Then double-clicked left corner to autofill to bottom.
  * I formatted the column to show numbers as percentages.

* Next, to make pivot tables easier to deal with 
  * I did a *copy* and *paste special as values* onto the “Percent change from Starting to Mid-Career Salary”  column to have the actual number in the cell instead of the formula. 

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

### Which majors have the highest percent change from starting to mid-career salaries? 
*To solve, I made a pivot table of “Undergraduate Major” and “% change from Start to Mid.” Then I sorted salary as descending to find top 5.*

![Degree%Desc](/DegPerDesc.jpg)

### Which majors have the lowest percent change from starting to mid-career salaries?
*To solve, I made a pivot table of “Undergraduate Major” and “% change from Start to Mid.” Then I sorted salary as ascending to find lowest 5.*

![Degree%Asc](/DegPerAsc.jpg)

I made some conclusions from playing around with the other data sets: 

"School Type" is somewhat humorous, as a type of school is *party*. This data set was problematic because some schools were listed twice, in two categories, such as *state* and *party*. I would need clarification from the source about what makes a school a "party school" before using it. 

The "Region" set is too limited in scope, without comparing it to the region one works in. So, I did not analyze this data set.

# Data Visualization 

Note: For my data visualization, I used Google Sheets :sweat_smile: and uploaded the file here. Then I created a chart in Datawrapper. https://datawrapper.dwcdn.net/hyMhf/1/

![DataViz](/Datawrapper-salaries-by-college-degree.jpg)

# Article Pitch

## How to turn college into financial success? Pick the right major and move to the right region.

### The biggest factors in financial success after college may be major and region you go to work in after graduation. Most prospective students cannot get into let alone pay for an ivy league school, or even afford to go far from home. But anyone can pick a useful major and find a hot job market after graduation. (Note: I would need to do data analysis on salaries by region and college degrees.) 

# Sources and Reports
### Have studied this area extensively and produced a report for the Hamilton Project. (PDF attached)
 * Brad Hershbein  (269) 343-5541 hershbein@upjohn.org
 * Melissa Keanery (301) 405-6202 kearney@umd.edu
 
### Wrote a report for The ETS Center for Research on Human Capital and Education. (PDF attached)
 * Neeta Fogg (215) 300-8879 neeta.p.fogg@drexel.edu
 * Paul Harrington  (215) 571-3874 clmp@drexel.edu 
 * Ishwar Khatiwada ishwar.khatiwada@drexel.edu

### Did an extensive analysis for the College Board, called Education Pays 2019 – The Benefits of Higher Education for Individuals and Society. (PDF attached)
 * Jennifer Ma jma@collegeboard.org
 * Matea Pender (202) 797-6197 
 * Meredith Welch (202) 293-1217, x. 344
 


