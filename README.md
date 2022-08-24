# Todo List

A simple todo app, using a rails back-end and react fron-end. View the app at https://react-todo-list-33.herokuapp.com/.

## Running the application
1. Clone this repository & the api which can be found at https://github.com/rjackson21/todo-api. 
2. `cd` into it and run the migrations (`bundle exec rake db:migrate`)
3. Install the dependencies by running `bundle`
4. Within `TodosContainer.js`, change the calls being made to the api. Currently, for the app to be deployed properly, the api is also deployed, and the app is calling to the deployed api. Change all api calls to './api/v1/todos'.
5. Start the Rails server by running `rails server` in the project root
6. Start React with `yarn start`


