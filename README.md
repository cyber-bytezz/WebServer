 # Simple Web Server

This repository contains a simple web server implemented in Python. The server listens for incoming connections on localhost and port 81 and responds with a basic HTML page containing the message "Hello from Hackers-Arise!".

## Getting Started

These instructions will help you set up and run the web server on your local machine for development and testing purposes.

### Prerequisites

- Python 3

### Running the Server

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/simple-web-server.git
   cd simple-web-server
   ```

2. Run the web server script:

   ```bash
   python3 webserver.py
   ```

   The server will start listening for incoming connections on localhost and port 81.

### Accessing the Web Page

Once the server is running, open a web browser and visit [http://localhost:81](http://localhost:81). You should see a page displaying the message "Hello from Hackers-Arise!".

### How It Works

The web server is implemented using the Python `socket` module. It follows these basic steps:

1. Create a TCP socket using `socket.socket()` and bind it to the localhost and port 81 using `bind()`.
2. Start listening for incoming connections using `listen()`.
3. Accept incoming connections using `accept()`, which returns a new socket for communication with the client.
4. Receive the HTTP request from the client using `recv()` and print it.
5. Send an HTTP response with a basic HTML page containing the "Hello Mello x ABC! message using `send()`.
6. Close the connection after sending the response.

### Customization

You can modify the message displayed on the web page by changing the content inside the `bytes()` function in the `webserver.py` script.

### Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

### License

This project is licensed under the [MIT License](LICENSE).
 ```HAPPY HACKING```
