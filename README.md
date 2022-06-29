# Bi Directional TCP Connection

This project contains a naive implementation of a tcp based chat system. The server accepts all incoming connection and broadcast messages from a client to all other connected clients.

## Try it out

```bash
git@github.com:bluebrown/go-tcp-chat.git
cd go-tcp-chat/
```

### Build

```bash
go build -o chat-server ./server/
go build -o chat-client ./client/
```

### Run

For the demonstration, use 3 terminal instances. Run the server in one terminal and a client in each of the 2 remaining terminals. Then type some messages.

```bash
# start the server
./chat-server
# run one more or clients in a separate terminal
./chat-client
```
