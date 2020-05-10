<h2> Overview of this Project </h2>

This is a simple Django application that shows portfolio with job details page and homepage. It uses Models, View and Template design pattern in Django which is similar to Model View Controller in other programming languages. However in Django the View acts as a controller, routing the requests to database to fetch the data and then the url mapping sends the data to templates which then displays data to the user whereas in other frameworks controller is the one that routes the incoming HTTP requests. 


Model | View | Template   
------ | ---- | -----------
Model classes maps data to data base tables | Python functions that are mapped to url | Presentation layer (generates HTML)