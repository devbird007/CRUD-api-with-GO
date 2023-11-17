# CRUD-api-with-GO

This is a CRUD api built with GO for a movies website.
There is no attached database so you perform CRUD operations on the server itself
using http requests.

The server processes data using the JSON format like so:
```
{
    "id": "2",
    "isbn": "45455",
    "title": "Movie Two",
    "director": {
      "firstname": "Steve",
      "lastname": "Smith"
    }
```

You can use API Clients like Postman or the Thunder-Client extension on vscode to perform
your CRUD operations on the server.
