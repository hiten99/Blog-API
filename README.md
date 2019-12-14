This is a very basic Blog application api with CRUD functionality. Each Post consists of title and content. You can create, edit, update and delete posts.

Prerequisites:

Ruby version 2.3.3
Rails version 5.1
Blog Api in Ruby on Rails

Steps to install the application:

1. Download and unzip or clone the repository.
2. Open command prompt in the code directory Run following commands:
3. bundle install
4. rails db:migrate
5. rails db:seed
6. rails s


Use Postman to test api endpoints
1. get: http://localhost:3000/api/v1/articles
2. post: http://localhost:3000/api/v1/articles
add headers: key=Content-Type value=application/json
body: {
"title": "this is test title2",
"content": "this is test body2"
}
3. delete: http://localhost:3000/api/v1/articles/15
4. put:http://localhost:3000/api/v1/articles/15
add headers: key=Content-Type value=application/json
body: {
"title": "this is updated title",
"content": "this is updated content"
}