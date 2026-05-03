# Star Wars REST API

REST API developed with Flask to manage Star Wars data.

## Features
- CRUD operations (Create, Read, Update, Delete)
- Database integration
- RESTful endpoints

Base URL:
http://localhost:3000

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

1. Clone the repository:
git clone https://github.com/danieltauil20/star-wars-api-rest

2. Install dependencies:
pip install -r requirements.txt

3. Run the server:
flask run

## Example response
```json
{
  "name": "Luke Skywalker",
  "planet": "Tatooine"
}


## Author
José Daniel Tauil Wozniak
