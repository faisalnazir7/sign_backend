
# Backend_Task_01

The task was to build a simple API which accepts the input in the given schema.


➔ Connected the backend application to mongodb through mongoose and the data gets stored from the incoming request in it.

➔ In the response send whether or not data was updated successfully.

➔ The schema for the request is:


		        {
          			email: string,
			        password: string,
			        username: string,
  			        age: number,
   			        hobby: string
		        }

➔ It contains a home page on which Two options are available **Login** and **Register**.

➔ Once user get registered credentials gets stored in database named **userDB**.

➔The **User Name** and **Password** entered while registering can be used to **Login** later.


## Tech Stack

**Client:** Bootstrap, HTML, CSS and JavaScript

**Server:** Node, Express, Mongoose, EJS


## Authors

- [@Faisal Nazir](https://www.github.com/faisalnazir7)


## Installation

Install with npm 

Download or clone repositories to your system and cd into directory.

```bash
  npm install 

```
```bash
  nodemon app.js

```
App will be ready at http://localhost:3000/
