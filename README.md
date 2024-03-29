### Todo_API - Using Node.js and Typescript - Task Management API

- The Todo API is a back-end application developed using TypeScript, Node.js, and Express.js, designed for efficient task management. This API allows users to interact with a list of tasks by viewing existing tasks, adding new tasks, and removing tasks from the list. Developed with TypeScript, the application ensures type safety and provides a robust foundation for building scalable and maintainable task management systems.

#### Installation

To run this project, install it locally using npm:

$ npm install
$ npm start

And run this in another terminal:

$ tsc -w

#### Models/Database Schema

There are 1 model:

1. Todo

#### Routes

1.  http://localhost:3000/todos : home route

2.  Route: ('/') -

 get all todos

- Request : get(/)

 addTodo - add a new todo

- Request : post(/) - create a new todo

3.  Route: ('/:id') -

 getTodoById - get a todo by id

- Request : get(/63a249d43246cd4eb4a02c81) - get todo by its id

 updateTodoById - update a todo by id

- Request : patch(/63a249d43246cd4eb4a02c81) - Update Todo Details by its id

 deleteTodoById - delete a todo by id

- Request : delete(/63a249d43246cd4eb4a02c81) - delete Todo by its id
