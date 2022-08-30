# Spring Boot Practice

## Total Time 
- Activity Time: 4 hours

## Tech Skills
- Spring Boot

## Goal
- To solidify Spring Boot

## Description
Associates will create a REST API using Spring Boot for tracking hi scores. An example of a sample score JSON is shown.
The API should support all CRUD operations.
- Create
- Read
- Update
- Delete

### Business Rules
- Negative scores should throw a 422
- If initials is longer than 3 charcters when createing a score then only the first 3 characters are used
- intials are always saved in the database as uppercase 
- People should be able to use a query param to sort by initials
- Scores should be shown in order of points descending
```JSON
{
    "id":101,
    "initials":"AAA",
    "points":1000
}
```


## Deliverables
- The Trainer will check in and see how associates are doing
