# Client-Server Program

A simple UDP Client-Server application to send a video file


### Prerequisite:

GCU Linux
C compiler

Edit the source file path variable in "CN Project Server.c" on line 123
For example, "/home/laraib/Desktop/sourceFileName.mp4"

Edit the destination file path variable in "CN Project Client.c" on line 70
For example, "/home/laraib/Desktop/destinationFileName.mp4"


### Compile the files using the following commands:
g++ "CN Project Server.c" -o server.out
g++ "CN Project Client.c" -o client.out


### Run the files using the following commands:
./server.out 9898
./client.out localhost 9898

