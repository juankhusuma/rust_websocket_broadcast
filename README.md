![Alt text](running.png)
How to run the server and clients
- Open 4 seperate terminals
- Set the current directory to the project directory for all terminals
- On the first terminal, run the server by typing `cargo run --bin server`
- On the other 3 terminals, run the clients by typing `cargo run --bin client`

When a message is typed and sent through the client, the server will recieve the message, prints it, then broadcast the message to all clients. All of the clients will then recieve the message and print it to the terminal.