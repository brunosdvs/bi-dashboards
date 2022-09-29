# PRODUCT MANAGEMENT - PROJECT MONITORING

1. BUSINESS, RULES AND PREMISSES

This company produces and sells chemical products. More specifically, welding filler metals. The products are constantly improved and new ones released according to market needs.
 
1.1. THE PROCESS
	
When a product is to be modified or a new product is to be created, a new Project is added to the portfolio. Depending on the product type, action steps for the product's release are predefined. Each action is followed in sequence and the time for their completion registered in the database. Once the product is released, the project is classified as completed. If the product is not released, the project is classified as canceled. Either way, final comments are registered. 


2. THE DASHBOARD

This is not an official dashboard for a real company. Data and business rules are made-up.

This dashboard showcases User Navigation skills, with edited interactions between views, button that change with state (default, highlighted, selected) navigation buttons, etc

DATA:
There was a User Friendly Excel sheet used to input data from the projects by the portfolio's manager. There were macros for recording historical data. The Excel file in this repository is a deprecated version of that.
Notice that 'Action_Log'[Time taken] might show big values for Projects 'In Progress' as it counts TODAY as the date for calculation of uncompleted actions.

PANELS:
PROJECT OVERVIEW
An overview of all portifolio. Can be filtered by time period. 
Clicking on the title of the "Expected Revenue" view will take you to a more detailed page on the subject. 
The "Portfolio evolution" view can inform, for example, if we are starting more projects than we are able to execute.

PROJECTS IN PROGRESS
This panel only shows projects that are currently in progress, along with detailed info on the individual actions for each.
The Burn-Down chart gives an overview on whether a project is on schedule. It can be improved by transforming the "NeededEffort'' curve into a straight line.

FINALIZED PROJECTS
This panel only shows projects that are currently set as Completed or Canceled.
The "Average Delay By Action" shows what actions inside the workflow are delayed the most, possibly indicating process bottlenecks.

EXPECTED REVENUE
Clicking on the title of the "Expected Revenue" view at the "PROJECTS OVERVIEW" panel will take you here. You can go back by clicking on the arrow at the top of the page.
A scatter chart shows how the expected demand of a product correlates with its price. It helps in understanding the Expected Revenue, and may lead to decisions on product price adjustment before it is released, also possibly changing the relevance and priority of a project.
