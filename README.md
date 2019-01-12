# My_JSON_Server

## How to use 
- install  
  ```
  npm install -g json-server
  ```

- prepare "db.json"
  ```
  {
    "list": [
      {
        "id": 1,
        "name": "matsukawa",
        "age": 26
      }
    ]
  }
  ```

- command 
  ```
  json-server --watch db.json
  ```

- Resources  
  http://localhost:3000/list
  
- GET / POST  
  - GET
    GET http://localhost:3000/list
  - POST
    POST http://localhost:3000/list -d name=test
