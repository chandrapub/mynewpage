I have created the ‘Pest Exterminator Database’ with some tables like customerInfo, pestInfo, serviceinfo, request info and login containing some initial data. I have followed the normalization rules to create tables. I have drawn relational diagram, showing the keys and relations amongst the tables. 
The site have a welcome page showing the pests from the database (with pictures). I have used Repeater show data. It also be possible to sign up as a new customer.
The site have a login and logout page for all users, Using Stored procedures.
If an exterminator logs in the person should be allowed to CRUD (create, read, update, delete) pests. Use a trigger to add a default picture link to a pest with no picture data.
The exterminator be able to see all requests for help, all requests from a given person and all requests for a given day.
If a customer logs in the person, it allow to CRUD own requests for help. I have used DataReader and GridView. A maximum of 4 requests per day are allowed.
