# HTTP/2 Protocol Implementation Project as lab4

## Task Description

The goal is to demonstrate that a custom website with its associated resources loads faster using the HTTP/2 protocol. The project is divided into two parts:

### Part 1: Setup and Configuration

1. Install the Nginx web server.
2. Create a custom SSL certificate.
3. Enable HTTPS/SSL.
4. Configure support for the HTTP/2 protocol in the Nginx server.
5. Activate the HTTP/2 protocol.
6. Confirm that support for the HTTP/2 protocol is enabled.

**Server Configuration:**
- Nginx directory: `/var/www/html/lab4`
- Nginx configuration file: `/etc/nginx/nginx.conf`
- SSL Certificate:
  - Public key: `/etc/ssl/certs/labos4.pem`
  - Private key: `/etc/ssl/private/labos4.pem`
- Operating System: Ubuntu 20.04.6 LTS

### Part 2: Web Page Creation

1. Create a directory named "lab4" in the HTML directory of the server.
2. Design a web page containing specific text, multiple CSS or JS files, and several individual image files (JPEG, PNG, more than 10).

### Testing and Logging

- Log the loading time of your webpage on the Nginx server when HTTP/2 is enabled and when only HTTP/1.x is supported.
- Generate two screenshots of the browser console: `http2.jpg` and `no_http2.jpg`, showcasing the logged page after loading with and without HTTP/2, respectively.

### HAR (HTTP Archive) Files

- Generate two HAR files: `no_http2.har` without HTTP/2 support and `http2.har` with enabled HTTP/2 support, following the lecture instructions.


