# Technologies

### Front-end
* React
* Redux
* use antd for designing. (https://ant.design/)
* SCSS

### Back-end
* Laravel
* Java
* Redis for caching

### Database
* MySql or PostgreSQL

# Goal

* You should create both the front-end and the back-end project separately.
* You should connect the back-end with the database using an .env file
* You should connect the APIs you are creating with an .env file in the front-end too.
* You should run both projects in two different servers too.

# Back-End
## APIs
use these apis to get the data as required.

* [https://dummyjson.com/products](Products) - use this api to get the product list
* [https://dummyjson.com/products/{productId}](Products) - use this route to get a single product data
* [https://dummyjson.com/products/search?q=Laptop](Products) - To create the search pass data in this format.
* [https://dummyjson.com/products/categories](Products) - Use this route to get the category list.
* [https://dummyjson.com/products/category/smartphones](Products) - Use this route to get data for an single category.

# Front-End
## Design

* Do the design as mentioned in the design folder.
* use the same API routes that you created.
* other than the data that have been provided in the routs the rest should be static.

## WorkFlow

* Install the react project using yarn.
* And when developing the project use reusable components.
* Try maintaining a separate SCSS file for fonts and colors.
* Develop this project on React version 16 or above.

## Project Structure

Redux functions and the front end code should be managed separately.
Assets, SCSS, JavaScript also should be managed separately.

Or

Try to manege a clean project structure.

## Uploading the project to github

* Create a new repo with your name and company name and share the repo with us.
* Don't upload the `node_modules` and the other auto generated files to git-hub.
* (add a .gitIgnore file in your project folder to avoid these auto-generated files.)
* And don't push the code to tha main this repo.