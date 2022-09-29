Prerequisites:
1. Golang
2. Basic knowledge Docker,and Docker installed on your system
3. Xampp or others


What we’ll build:
1. MySQL as our databas
2. GORM as an ORM to interact with our database
3. Request router using gorilla/mux
4. Logrus for logging

The specifications for our API Server are:
1. It listens to port 8000 on the localhost
2. It has five endpoints: healthz, createItem, getCompletedItems, getIncompleteItems, updateItem, and deleteItem
3. The TodoItem model consists of Id, Description, and Completed status attributes
  

How to lauch this project on you localhost
1. Move all of this file to your "htdocs/" at xampp folder (Im Using xampp)
2. Open your Xampp Control Panel, and run Apache
3. To run the file, please run the todolist.exe and open localhost:80/todolist-mysql-go/todo/index.html. (because my http port at xampp is 80)

Note:
1. Remember to run our docker container that we use
2. Run todolist.exe


All this code, from https://betterprogramming.pub/build-a-simple-todolist-app-in-golang-82297ec25c7d, I did this project to practice how to use golang using this tutorial
