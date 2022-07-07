

# View Deployment

https://react-todo-list-33.herokuapp.com/

## Run Locally

To run this app locally, you will want to clone both this repo and the api which can be found at https://github.com/rjackson21/todo-api. 

Within 'TodosContainer.js' you will want to change the calls being made to the api. Currently, for the app to be deployed properly, the api is also deployed, and the app is calling to the deployed api. Change all api calls to './api/v1/todos' with both the rails serve and the front-end server running. 

To run the back end locally, use:

### rails s 

To run the front end locally, use:

### yarn start

