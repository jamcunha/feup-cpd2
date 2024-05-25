# CPD Assignment 2 - Concurrent and Fault Tolerant Client-Server System using TCP in Java

| Name             | Number    |
|------------------|-----------|
| Joaquim Cunha    | 202108779 |
| Miguel Garrido   | 202108889 |

## Note

While the ranked system is not implemented, there is already code to support it in the server, database and game.

- Missing on the server is a way to increase rank interval to search the queue by time instead of incrementing every iteration of the while loop and a way to choose between a simple game and a ranked game.
- Missing on the Client is a way to choose between a simple game and a ranked game.

## Compilation

To compile the project, run the following command in the root directory of the project:

```bash
javac Server.java Client.java Game.java Player.java Queue.java Database.java SocketUtils.java

# alternatively, you can use the provided Makefile
make
```

## Execution

To run the server, execute the following command:

```bash
java Server <port>

# alternatively, you can use the provided Makefile which will run the server on port 8080
make server
```

To run the client, execute the following command:

```bash
java Client <server_address> <server_port>

# alternatively, you can use the provided Makefile which will run the client on localhost:8080
make client
```

## Already Stored Users

| Username | Password |
|:--------:|:--------:|
| user1    | yes      |
| user2    | no       |
