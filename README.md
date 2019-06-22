**Adobe Analytics Report API via PowerBI Python Script**

A problem we currently facing in Power BI is the lack of dynamical updates for Adobe Analytics data. While there exists an Adobe Analytics Report Connector for Power BI it lacks the ability to set a moving time period. This results in a tedious resetting of the date range in the Adobe Analytics Connector which takes a lot of time. This project will speed things up via the ability to load Python scripts in Power BI. Just grab a request json from the Adobe Analytics Workspace and place it as a text file for this scripts. See here how to retrieve a json request body:
https://helpx.adobe.com/analytics/kt/using/build-api2-requests-analysis-workspace-feature-video-use.html