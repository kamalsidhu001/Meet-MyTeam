﻿# Static File Server in Go

This project is a simple static file server built with Go. It serves static files such as HTML, CSS, JavaScript, and images from a designated `static` directory.

## Features

- Serves static files from the `static` directory.
- Accessible at `http://localhost:8080`.
- Minimal setup and lightweight.

## Prerequisites

- [Go](https://go.dev/doc/install) installed on your machine.

## Setup Instructions

1. **Clone the Repository**  
   Clone the project repository or copy the `main.go` file to your working directory.

2. **Create a `static` Directory**  
   Ensure you have a `static` directory at the project root. Place your static files (HTML, CSS, JS, images, etc.) in this folder.

   Example structure:

3. **Run the Server**  
Use the following command to start the server:

```bash
go run main.go

Server is running on http://localhost:8080

