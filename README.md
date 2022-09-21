Steps 
-----

1. On CMD run - 

npm i -g json-server

2. Create the folder <your-company's-name>-server in a suitable location. 

3. save the file db.json in that folder. 

4. Open that folder on CMD. 

5. On CMD run -

json-server --watch db.json --port 12345

6. Access the APIs on your front-end project as follows: 

GET    http://localhost:12345/posts

GET    http://localhost:12345/posts/1

POST   http://localhost:12345/posts

PUT    http://localhost:12345/posts/1

DELETE http://localhost:12345/posts/1

GET    http://localhost:12345/users

GET    http://localhost:12345/users/1

POST   http://localhost:12345/users

PUT    http://localhost:12345/users/1

DELETE http://localhost:12345/users/1

GET    http://localhost:12345/comments

GET    http://localhost:12345/comments/1

POST   http://localhost:12345/comments

PUT    http://localhost:12345/comments/1

DELETE http://localhost:12345/comments/1

7. View this documentation for more info: 

https://www.npmjs.com/package/json-server


