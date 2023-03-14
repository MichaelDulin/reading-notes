# Class 3.12 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 12**
- [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
- [Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)


**Status Codes Based On REST Methods**
1. In your own words, describe what each group of status code represents:
  - 100’s = Informational status codes, first code when a new request is made 
  - 200’s = Success codes, affirmation
  - 300’s = Redirection codes, location for resources could not be found 
  - 400’s = Client error codes, something went wrong during request to server
  - 500’s = Server error codes, error is on server side
2. What is a status code 202?
  - Accepted, request was valid but processing is not complete yet
3. What is a status code 308?
  - Permanent redirect
4. What code would you use if an update didn’t return data to a client?
  - 204: no content
5. What code would you use if a resource used to exist but no longer does?
  - 410: gone client
6. What is the ‘Forbidden’ status code?
  - 403: forbidden response
  
  
**Build A REST API With Node.js, Express, & MongoDB - Quick**
1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
  - To hide access to the key
2. What is middleware?
  - Known as software glue, a tool which allows other applications to communicate
3. What does app.use(express.json()) do?
  - Parses incoming requests and stores parsed data 
4. What does the /:id mean in a route?
  - Acts ass a path using an id to function
5. What is the difference between PUT and PATCH?
  - Put changes resources while patch transforms the resources
6. How do you make a default value in a schema?
  - Using set, if there is not content passed
7. What does a 500 error status code mean?
  - Server encountered an unexpected condition that prevented it from finishing request
8. What is the difference between a status 200 and a status 201?
  - Similar, however, 201 has created a new resource



## Things I want to know more about
