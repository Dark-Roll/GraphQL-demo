# GraphQL demo

## How to start?

1. yarn install
2. yarn dev # start server
3. yarn json # start API and DB

API is on http://localhost:3000/users
Query page is on http://localhost:4000

This is follow Udemy tutorial.

### Example Query
{
  user(id: "40"){
    id,
    firstName
    company{
      id
      name
    }
  }
}

mutation{
  addUser(firstName: "Stephen", age: 24){
    id
    age
  }
}
