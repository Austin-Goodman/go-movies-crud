# go-movies-crud
Simple CRUD app for movies built in golang

# Methods
## GET
### /movies
- Returns all movies
### /movies/{id}
- Returns movie by {id}
## POST
### /movies
- Create movie
- JSON ex:
    ```
    {
        "isbn": "12345",
        "title": "Example Movie",
        "director": {
            "firstname": "John",
            "lastname": "Doe"
        }
    }
    ```
## PUT
### /movies/{id}
- Update Movie by {id}
- JSON ex:
    ```
    {
        "id": "0",
        "isbn": "12345",
        "title": "Example Movie Update",
        "director": {
            "firstname": "Jane",
            "lastname": "Smith"
        }
    }
    ```
## DELETE
### /movies/{id}
- Delete movie by {id}