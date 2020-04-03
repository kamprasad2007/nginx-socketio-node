### Nginx reverse proxy + Socket.IO + NodeJs Web server

[![Greenkeeper badge](https://badges.greenkeeper.io/kamprasad2007/nginx-socketio-nodejs.svg)](https://greenkeeper.io/)

This application is to simulate Socket.IO and NodeJs Webserver work with nginx reverse proxy.


- Nodejs Webserver runs on 8080 port
- socker.IO runs on 8090 port
- nginx reserve proxy runs on 8000


Docker is used to make isolate environment and nginx to redirect each request base on path to right server.

### How to run

```sh
docker-compose build
docker-compose up
```


### In web browser

```sh
http://localhost:8000
```
