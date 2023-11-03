# Nginx Proxy for Hackle
An example of nginx configuration that serves as a proxy for Hackle's event tracking endpoints.

## Getting Started

1. Clone repository

   `git clone https://github.com/hackle-io/hackle-event-proxy`

2. Build Docker image

   `docker build -t hackle-event-proxy`

3. Run container

    `docker run --name my-hackle-event-proxy -d -p 8080:80 hackle-event-proxy`

4. Visit 

    `http://localhost:8080`

Yo should see:
```
Hello, Hackle!
```
This is same response you would get from visiting https://event.hackle.io/ (which means your proxy is working as expected).

