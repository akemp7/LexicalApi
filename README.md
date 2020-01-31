# _A Word Rating API_

#### _An exercise in creating and calling an API using C#_

#### By _Anita Kemp, Loewy Malkovich, Jen Batara_

## Description

_This API is a database of words that people hate (e.g. "moist"). Users can rate these words based on a scale of 1-5 through the implementation of emojis. A 1 shows a disgusted emoji whereas a 5 shows a happy emoji. Users can POST new words to the API, and their rating will be averaged with other user ratings for existing words already in the API._

## API Endpoints and Responses
 Endpoint: localhost:5000/api/words
 
 Responses: 

## Setup/Installation Requirements
For the MVC app: 

* _Clone this repository_
* _Navigate to the Lexical directory_
* _In command line, run: "dotnet ef migrations update" in order to generate the database in MySQL_
* _Then run the following: "dotnet run"_
* _In a separate terminal, navigate to the LexicalClient directory_
* _Run the command: "dotnet run" _
* _Navigate to localhost:5004_

To examine the API itself: 
* _One can also navigate to Swagger at: localhost:5000/swagger to see all functionality for this API._

## Support and contact details

_Please leave a comment on this repository if there are any questions._

## Technologies Used

_C#, .NET, MVC, MySQL, Entity_

### License

*MIT*

Copyright (c) 2019 **_Anita Kemp, Loewy Malkovich, Jen Batara_**
