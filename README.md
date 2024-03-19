# A Simple Webserver in C Programming

This is a very basic web server written in C that listens for incoming HTTP requests and serves files from its current directory. It's a demonstration of low-level socket programming in C, handling TCP connections, file I/O, and basic HTTP request parsing.



## Features

- Listens on port 8080 (hexadecimal `0x901f`) for incoming connections.
- Parses simple HTTP GET requests.
- Serves files from the server's current directory.

## Prerequisites

Before running the server, ensure you have a C compiler (such as GCC) installed on your system. This server is designed to run on Unix-like systems such as Linux or macOS.

## Compiling the Server

To compile the server, navigate to the directory containing `webserver.c` and run the following command:

```bash
gcc webserver.c -o webserver

