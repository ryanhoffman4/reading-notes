
#### Status Codes Based On REST Methods

#### In your own words, describe what each group of status code represents:

#### 100’s =
- these status codes are only informational
- they usually just give a confirmation that the header of the request has been received

#### 200’s =
- these status codes tell the client that the request has been accepted

#### 300’s =
- these status codes are called redirection codes
- they tell the client that the client's request is not availabel at the server's location anymore

#### 400’s =
- these are error codes for the client, often for invalid requests

#### 500’s =
- these are error codes for the server
- usually these are for overwhelmed servers

#### What is a status code 202?
- this tells the client that the request was valid

#### What is a status code 308?
- this tells the client to search for material at a different URL

#### What code would you use if an update didn’t return data to a client?
- Code 204: No Content

#### What code would you use if a resource used to exist but no longer does?
- Code 308: Permanent Redirect

#### What is the ‘Forbidden’ status code?
- "Forbidden" is Code 403
- it means the clent has authorization to be at that location, but no permissions to view the material




#### Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

#### Why do we need to pull our MongoDB database string out of our server and put it into our .env?
- we do not only want to communicate to the local server
- putting the database string into the .env file allows the application to communicate with outside servers

#### What is middleware?
- middleware are functions that receive both req and res objects as parameters, and usually utilize callback functions

#### What does app.use(express.json()) do?
- this lets the server accept json as a body

#### What does the /:id mean in a route?
- this is a parameter that gives javascript access to whatever the client passes in 

#### What is the difference beween PUT and PATCH?
- patch only updates specifically what the user has sent, while put updates all of the information about the client at once

#### How do you make a defalut value in a schema?
- use the default: key

#### What does a 500 error status code mean?
- it means that their is something wrong with the internal server/database itself

#### What is the difference between a status 200 and a status 201?
- 200 means everything was successful
- 201 specifcally means that you have successfully created an object

[Back to Table of Contents](https://ryanhoffman4.github.io/reading-notes/)