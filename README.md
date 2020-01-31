# _A Word Rating API_

#### _An exercise in creating and calling an API using C#_

#### By _Anita Kemp, Loewy Malkovich, Jen Batara_

## Description

_This API is a database of words that people hate (e.g. "moist"). Users can rate these words based on a scale of 1-5 through the implementation of emojis. A 1 shows a disgusted emoji whereas a 5 shows a somewhat happier one. Users can POST new words to the API, and their ratings will be averaged with other user ratings for existing words already in the API._

## API Endpoints 
localhost:5000/api/words

## Setup/Installation Requirements
For the MVC app: 
Clone this repository
In command line, run: "dotnet ef migrations update" in order to generate the database in MySQL
Then run the following: "dotnet watch run"
Navigate to localhost:5000/

To examine the API itself: 
One can also navigate to Swagger at: localhost:5000/swagger to see all functionality for this API. 

## Support and contact details

_Please leave a comment on this repository if there are any questions._

## Technologies Used

_C#, .NET, MVC, MySQL, Entity_

### License

*MIT*

Copyright (c) 2019 **_Anita Kemp, Loewy Malkovich, Jen Batara_**
