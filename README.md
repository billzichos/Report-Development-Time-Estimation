# Report-Development-Time-Estimation
How long will a report take to develop?

## Synopsis
I work with a team of systems analysts.  One of the services we provide our company is report development.  The report development process consists of requirements gathering, design, development and testing efforts, which are more often than not, iterative.  Like anything, getting an idea across the finish line takes time, often a surprising amount of time.  Therefore, the question is - Can I provide and reasonably accurate estimate of how long it will take to develop at report from start to finish.  My guess is that we can.

## Data Collection
Luckily, I have seven years of data collected in a SharePoint workflow I built to manage the report development process.  Therefore, the data collection effort is simply an matter of extracting the features I feel are relevant from SQL database.  I believe I have a few thousand records that capture the following about each report development effort

WHO?
- Developer - Who did a majority of the report development?
- Owner - Who is the business owner of the report?
- Tester - Who is responsible for testing the report?
- Developer Count - How many developers did we have at the time?

WHAT?
- New or Change - Is the work for a new report or more simply, a change to an existing report.
- Data Source - What data are we dealing with?
- Report Pipeline - How many other reports were being worked on at the time?

WHEN?
- Created Date - This will give us all the temporal information we need to know about the report development effort.  Day of Week, Month, Quarter, and Year are date attributes that will help describe the business conditions and our likely workload surrounding the report request.