# Simple HTTP Server from scratch in Java 

This project contains a simple HTTP server implemented in Java. It demonstrates the use of `ServerSocket` and `Socket` classes to handle basic HTTP requests.

## Features
- Listens for incoming connections on port 8080.
- Responds to each HTTP request with the current server date and time.

## How It Works
- The server runs an infinite loop, accepting incoming socket connections.
- For each connection, it sends a basic HTTP 200 OK response containing the current date and time.
- There is an optional (commented) code block to print out the HTTP request headers received from the client.

## Usage
1. Compile the Java file:
   ```sh
   javac src/sideProjects/SimpleHTTPServer.java
   ```
2. Run the server:
   ```sh
   java -cp src sideProjects.SimpleHTTPServer
   ```
3. Open a web browser and navigate to [http://localhost:8080](http://localhost:8080) to see the server's response.

## Screenshots 
This is what the response will look like on the browser. 

![Connecting to the server from PowerShell](Browser%20Response.png)

This is what the response looks like on PowerShell. 

![Connecting to the server from PowerShell](PowerShell%20Response.png)

## Author
Janny Jonyo

## Notes
- This server is for demonstration and educational purposes only. It is not suitable for production use.
- Only one request is handled at a time (no concurrency).
- The server always responds with the current date and time, regardless of the request. Please feel free to customise it to your liking! 


