### API Design Best Practices


#### What does REST stand for?
- REST stands for Representational State Treansfer

#### REST APIs are designed around  ____.
- resources!, which have different identifiers parsed by rest apps

#### What is an identifer of a resource? Give an example.
- a resource is anything that is accessed by a client
- in the example of city explorer, geocode data is a resource

#### What are the most common HTTP verbs?
- GET: receives info
- PUT/POST: gives info
- DELETE: removes info
- PATCH: updates info

#### What should the URIs be based on?
- they should be based on nouns, and not verbs

#### Give an example of a good URI.
- from the reading example: https://adventure-works.com/orders

#### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
- a chatty web API gives many small resources at once, and can be difficult to parse
- therefore, it is generally considered a bad thing

#### What status code does a successful GET request return?
- it typically returns HTTP status code 200

#### What status code does an unsuccessful GET request return?
- it returns the infamous 404 (not found)

#### What status code does a successful POST request return?
- it typically returns HTTP status code 201

#### What status code does a successful DELETE request return?
- it typically returns HTTP status code 204

[Back to Table of Contents](https://ryanhoffman4.github.io/reading-notes/)