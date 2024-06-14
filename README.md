# Project description: GrubDash Backend 
This application serves as backend layer to GrubDash Frontend application repository can be found at [GrubDash frontend](https://github.com/Thinkful-Ed/starter-grub-dash-front-end).

This application sets up an API and building out below routes.
- get /dishes: Lists array of the available dishes with each dish with properties id, name, description, price and image_url
- get /dishes/:dishId: Returns dish details having id that matches dishId
- create /dishes: Creates new dish with properties id, name, description, price and image_url
- update /dishes/:dishId: Modify dish having id that matches dishId
- get /orders: Lists array of the orders with each order with properties id, deliverTo, mobileNumber, status and dishes
- get /orders/:orderId: Returns order details having id that matches orderId
- create /orders: Creates new order with properties id, deliverTo, mobileNumber, status and dishes
- update /orders/:orderId: Modify order having id that matches orderId
- delete /orders/:orderId: Deletes order having id that matches orderId

## Run application locally
- Clone the repository
- Open teminal and change directory to project folder
- run command `npm i` to install dependencies
- run command `npm run dev`
- In postman fetch dishes details call `GET` Api at `http://localhost:5000/dishes` endpoint

## Run tests locally
- Clone the repository
- Open teminal and change directory to project folder
- run command `npm i` to install dependencies
- run command `npm test`

