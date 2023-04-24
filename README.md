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

* Get list of doctors
    * doctor name
    * hospital name
* Make an appointment.
    * check the doctor availability with the date and time. - If available we need to get a message known as available. if we should get an error message

# Front-End
## Design

### Task -1
* Develop the form which we have given you in the forms folder using next js.
* Please develop it as a separate module.
* Please add the upload CV section and and the mobile number should be verified.
* The clear button in the design also should be functional as in the design.
* And you should add a a proper form validation as well in the way we have displayed in the form
### Task -2
* Do the design as mentioned in the design folder.
* use the same API routes that you created.
* other than the data that have been provided in the routs the rest should be static.
* Before you click on the submit button in the home page you need to do an human verification please use cloudflare fot this
(https://www.cloudflare.com/en-gb/products/turnstile/?utm_source=turnstile&utm_campaign=widget)
* You need to send a email for both applicant(upload success) and the organization(new applicant) please develop the email templates separately. (please use the given email template to send the email for the both applicant and the organization.)

## WorkFlow

* Install the react project using yarn.
* And when developing the project use reusable components.
* Try maintaining a separate SCSS file for fonts and colors.
* Develop this project on React version 16 or above.
* Please work on the front-end task in the order we have mentioned and let us know when its completed

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
