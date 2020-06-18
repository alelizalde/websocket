# websocket

Using WebSocket to build an interactive web application
This code has a “Hello, world” application that sends messages back and forth between a browser and a server. WebSocket is a thin, lightweight layer above TCP. This makes it suitable for using “subprotocols” to embed messages. In this guide, we use STOMP messaging with Spring to create an interactive web application.

This project has a server that accepts a message that carries a user’s name. In response, the server will push a greeting into a queue to which the client is subscribed.

rund at http://localhost:8080 by default
