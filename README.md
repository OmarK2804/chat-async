# Module 10 - Asynchoronous Programming

## 2.1. Original code of broadcast chat.

![](imgfiles/Screenshot%202024-05-08%20112037.png)
I open 1 terminal to run the server in vscode and 3 terminal to run the client side. We can see from the picture that if we type a message from one of the clients, the server will send it to all of the clients.

## 2.2. Modifying the websocket port

After modifying the port on the server side to `8080`, we also have to change the port on the client side in order to have a connection to the server. In the line of code where we specify the link for the localhost port, we can see that the client side use a WebSocket Protocol while the server side use a TCP(Transmission Control Protocol).