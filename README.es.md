# Star Wars REST API

REST API developed with Flask to manage Star Wars data.

## Features
- CRUD operations (Create, Read, Update, Delete)
- Database integration
- RESTful endpoints

## Endpoints

### Get all characters
GET /characters

### Get character by ID
GET /characters/<id>

### Create character
POST /characters

### Update character
PUT /characters/<id>

### Delete character
DELETE /characters/<id>

## Technologies
- Python
- Flask
- SQL

## How to run
1. Clone the repository
2. Install dependencies
3. Run the server

## Example response
```json
{
  "name": "Luke Skywalker",
  "planet": "Tatooine"
}
