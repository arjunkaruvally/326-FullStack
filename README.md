# Grocery-List

This assignment uses the concepts studied so far in the course to create a Full Stack Web Application. This includes NodeJS, MongoDB in backend and HTML, CSS, Javascript in the frontend.

The task is to create a grocery list app that multiple users can use and edit. The users are authenticated using a username and password that will be stored in a database(MongoDB). The grocery list is also stored in the database with options available for each user to add and delete items.

This is created as a RESTful web API which means the server has API endpoints that can be used to manipulate the database using a decoupled frontend. The task of the server is only the manipulation of data with no frontend computations. Communication between frontend and backend is done using AJAX calls to the API endpoints.

## Setting up
- clone the repository using github `git clone https://github.com/arjun23496/326-FullStack.git`
- install the required node modules `npm install`
- Make sure node version is `12.13.0` and mongo version is `4.2.1`
- Make sure you have some application like [POSTMAN](https://www.getpostman.com/downloads/) to test the backend APIs
- Create a database in mongo named `grocerylist`\
- (Optional) Run the server and create a user by sending POST request to `/api/signup` endpoint. This can be easily done with POSTMAN