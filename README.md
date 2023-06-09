# React Go App

This is a simple application that demonstrates the separation of concerns between a Go backend and a React frontend done for learning purposes.

## Prerequisites

Make sure you have the following software installed on your system:

- [Go](https://go.dev/dl)
- [Node.js](https://nodejs.org)

## Usage

1. Run the Go backend server
```
$ cd backend
$ go run main.go
```

2. Run the React frontend
```
$ cd frontend
$ npm install
$ npm start
```

3. Access the React URL provided to you, usually it will be http://localhost:3000/ unless there is a port conflict then it will choose another port to run the frontend

Accessing the URL in the browser you should see:
- Items:
  - Item 1
  - Item 2
  - Item 3

That means the frontend connected with success to the Go backend and got the list of items from the backend running in http://localhost:8080/api/items

## Folder Structure

- `backend/`: Go backend code.
- `frontend/`: React frontend code.

## API Endpoint

The Go server exposes a single API endpoint:

- `GET /api/items`: Fetches a list of items in JSON format.

## Customize

You can customize the application by modifying the Go backend code (`main.go`) and the React frontend code (`frontend/src/App.js`). Add new features, create additional API endpoints, or enhance the UI as per your requirements.
