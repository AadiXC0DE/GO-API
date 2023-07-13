# GO_API

GO_API is a simple API written in Go (Golang) that provides functionality to manage a collection of books. It allows users to retrieve books, add new books, update the quantity of books, and return books.

## Prerequisites

Before running the GO_API, ensure that you have the following installed on your machine:

- Go (Golang)
- `gin` package: `go get -u github.com/gin-gonic/gin`

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/AadiXC0DE/GO_API.git
   ```

2. Navigate to the project directory:

   ```
   cd GO_API
   ```

3. Build and run the application:

   ```
   go run main.go
   ```

## Features

- Retrieve a list of all books
- Get information about a specific book by ID
- Add a new book to the collection
- Check out a book (decrease the quantity by 1)
- Return a book (increase the quantity by 1)

## Response Format

The API returns responses in JSON format. The following are the possible response codes:

- `200 OK`: The request was successful.
- `201 Created`: The resource was successfully created.
- `400 Bad Request`: The request was invalid or missing parameters.
- `404 Not Found`: The requested resource was not found.

The response body will contain the requested resource or an error message in case of failure.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
