# Own HTTP Server

This project implements a simple, lightweight HTTP server in Java. The server is capable of handling basic GET requests and responding with appropriate HTTP responses. It's designed to be extensible, so you can easily add more HTTP methods or enhance the functionality.

My goal for this project is to keep it lightweight, highly scalable, secure, and easily customizable. I want users to be able to add their own implementations or features without disrupting the existing codebase.

## Features
- Handles multiple concurrent TCP connections.
- Supports basic HTTP GET requests.
- Threaded request handling for better performance.
- Lightweight and simple, with no external dependencies.

## Requirements
- Java 17 or higher

## How It Works

This HTTP server works by listening on a specified port (default is `8080`) and handling incoming client requests in separate threads. Each request is parsed, and if it's a valid GET request, the server responds with a simple message or the requested resource.

## Usage

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/Http-Server.git
cd Http-Server
```
Before making any contributions, please read the [Contributing.md](https://github.com/ajaynegi45/Http-Server/blob/main/contributing.md) file, which contains important guidelines to make the contribution process smoother, especially for newcomers.

# Acknowledgements

This project wouldn't be possible without the contributions of our amazing community. Thank you for being part of our journey! 🙌

<a href = "https://github.com/ajaynegi45/Http-Server/graphs/contributors">
  <img src = "https://contrib.rocks/image?repo=ajaynegi45/Http-Server"/>
</a>

<br/>

# Flow Diagram
<img src="https://github.com/ajaynegi45/Http-Server/blob/main/project-structure/httpserver.png"  alt="Diagram" />
