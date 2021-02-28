# Server-Client-Communication
This is a Server-Client-Communication project based on TCP protocol and UDP protocol.

## How to use and run
-Download the entire project either in zip or clone repo format, run your terminal in linux and navigate to downloaded folder.Use the command:<br/>
```
"Download-Location"/Server-Client-Communication-main/Server-Client-Communication-main/ServerClientTCP
```
Or
```
"Download-Location"/Server-Client-Communication-main/Server-Client-Communication-main/ServerClientUDP
```
-Compile the server code using the commands: <br/>
```
gcc My-Server.c -o Server
```
-Compile the client code using the command:<br/>
```
gcc My-Client.c -o Client
```
-Run server with a server port using the command:<br/>
```
./Server 2000
```
-run Client with name of server and server port using command.<br/>
```
./Client localhost 2000
```

## Tech Stack used
-All the functionalities offered by the C language and the socket programming libraries.
