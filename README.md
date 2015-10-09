# Report-Development-Time-Estimation
How long will a report take to develop?

## Synopsis
I work with a team of systems analysts.  One of the services we provide is report development.  I believe we add significant value to the information systems we have purchased, like ERP and CRM, by making the data they collect more accessible and consumable (aggregated and visualized).  The report development process consists of requirements gathering, design, development and testing efforts, and more often than not, require a couple iterations.  Like anything, getting an idea to the showroom floor takes time - often a surprising amount of time.  Therefore, the question is, "Can I provide a reasonably accurate estimate of how long it will take to develop at report from start to finish?"  My guess is that we can.

## Data Collection
Luckily, I have seven years of data collected, representing a few thousand reporting initiatives, in a SharePoint workflow I built to manage the report development process.  Therefore, the data collection effort is simply a matter of extracting the features I feel are relevant from a SQL database.  But first, let's define a *reporting initiative* as a request for a new report or a change to an existing report.

The following attributes are known about each of our reporting initiatives as well as our target variable, *Duration*, how long the report took to develop.

WHO?
- Developer - Who did a majority of the report development?
- Owner - Who is the business owner of the report?
- Tester - Who is responsible for testing the report?
- Developer Count - How many developers did we have at the time?

WHAT?
- New or Change - Is the work for a new report or more simply, a change to an existing report.
- Report Pipeline - How many other reports were being worked on at the time?

WHEN?
- Created Date - This will give us all the temporal information we need to know about the report development effort.  Day of Week, Month, Quarter, and Year are date attributes that will help describe the business conditions and our likely workload surrounding the report request.

WHERE?
- Data Source - What data are we dealing with?

WHY?
Well ain't that a novel concept.
