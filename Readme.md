# Gorilla Websockets with Gin

This project demonstrates how to use Gorilla Websockets with the Gin framework in Go.

## Getting Started

### Prerequisites

- Go 1.23.5 or later

### Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/Ris-Codes/gorilla-websockets.git
    cd gorilla-websockets
    ```

2. Install dependencies:
    ```sh
    go mod tidy
    ```

### Running the Application

To run the application, use the following command:
```sh
go run main.go
```

The server will start at `localhost:8080`.

WebSocket Endpoint
The WebSocket endpoint is available at:

Example Usage
Open a WebSocket client (e.g., https://websocketking.com/, a browser or a WebSocket client tool).
Connect to `ws://localhost:8080/ws`.
Send a message to the server.
The server will echo the message back to the client.
Built With
Gin - HTTP web framework
Gorilla WebSocket - WebSocket implementation