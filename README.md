# Google-Book-Search

https://rocky-depths-55419.herokuapp.com/

  [![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](#license)

  ## Description
    The objective in this project was to refactor the code to convert the application from RESTful API practices to a GraphQL API. In the back-end, the auth middleware function has been updated to work with GraphQL API. The Apollo Server was implemented and applied to the Express server as middleware. Query and mutation functionality was defined in a Schemas directory to with the existing Mongoose models. The necessary Query and Mutation types were defined in typeDefs. In the front-end, the GraphQL query and mutations were set up to use the Apollo Server in the utils directory. The js files in the Pages directory were updated to import and utilize the GraphQL functionality defined in the back-end. Finally, an Apollo Provider was created to make every request work with the Apollo Server.



  
      


User can sign up or log in

![signup-login](https://user-images.githubusercontent.com/105762638/206319110-2474106a-dcff-4bc5-8eec-0e1850a820c3.png)


While logged in, user can save books from search results

![search-results](https://user-images.githubusercontent.com/105762638/206319107-7addd35a-cfcb-4d85-b0ee-cf4be1813039.png)


While logged in, user can view books save in their account and remove them as they wish.

![saved-books](https://user-images.githubusercontent.com/105762638/206319111-45aca08d-2440-4d87-8532-05349ccddd7e.png)


  ## Table of Contents
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [Projects](#projects)
  

  ## Installation
  No installation required!

  ## Usage
  Instructions for use Google Book Search:

  Sign up with a new username, email, and password. Once logged in, user can search books to be presented with several search results and save them in their account. User is also able to delete books from their saved list as long as they are logged in. 

  ## License
    This application is covered under MIT. To read view documentation about this license, please visit the link below.
  https://opensource.org/licenses/MIT

  ## Tests
  No tests are available at this time.

  ## Projects

  To view my other work, please visit my GitHub profile at [ConnieMarie](https://www.github.com/ConnieMarie). 
