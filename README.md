# Overview of Project
---
## Objective
The objective of this project was to refactor the original macro created for Steve. Originally the code was written to collect desired information from the "Stocks 2017" and "Stocks 2018" workbooks. By refactoring the code it was made more flexible and was allowed to run more efficiently. This transformation is desriable to Steve as it allows him to run the data repeatedly with ease while still gathering the desired information and reducing the workload on his local machine.
---
## Data
The original data sets where gathered from 12 different stocks that contained their ticker, opening price, the high and low price for a given day, the closing price, the adjusted closing price, the volume of shares traded, and the date that the transactions took place. For the purposes of this analysis, we were only interesting in the ticker, the total volume of daily trades, and the return of each stock.
---
# Procedure
The refactoring began with taking the original code and outlining the sections that needed to be adjusted to make the code become more efficient. Using comments, the sections where outlined and labelled for ease of identification later should the code need to be refactored or adjusted later on to fit rising needs. Below is a snapshot of the main body of code after it had been refactored, with comments:
---
<img width="560" alt="Main_Body" src="https://user-images.githubusercontent.com/112291888/190880696-27dc7905-eea8-4b49-992d-71e93fc6cd7c.png">

---
# Summary
At the end of refactoring, the macro ran substantially quicker while maintaining its usability. For future ease of use, a "Run Analysis" button was included in the "All Stocks Analysis" workbook as well as a "Reset/Clear" button to reset the worksheet and clear all of the formatting for the next run of the data.
---
## Why we Refactor
We refactor code for many reasons; it makes our code run faster, makes the code cleaner and easier to read, and most importantly, it can reduce the size of our files for easier transmission and use in the future. There are situations were refacrtoring code may not be needed or may not be possible. Simple macros that deal with smaller data sets may not need to be refactored as they are not large to begin with. Conversly, data sets that are extremly large and require extensive macros to analyse them may not be able to be refactored as it can reduce the level of depth of the needed analysis. 
---
## Advantage of Refactoring 
The advantageof refactoring the code in this case and the reason we undertook the task was because it drastically reduced the run time of our macro and made the code more efficient to run and easier on whichever local machine the code is being used on. Before refactoring the run time for each year analysis was approximately 1.1 seconds; refactoring the code reduced that by almost 5 times bringing it to approximatly 0.2 seconds. Below are included screenshots of the completed run times after refoctoring.
---
<img width="439" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/112291888/190880899-5e753a8f-2324-488e-bc4b-692abe4d65bf.png">
<img width="429" alt="VBA_Challange_2018" src="https://user-images.githubusercontent.com/112291888/190880912-a9df84ae-8439-4494-ba07-05293d76dd36.png">
