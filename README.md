# Mutithreaded-Chatroom

# Project-Description

This a Chatroom built in C++ using the concept of Multithreading and Synchronization, Multiple Users can Chat using this application.

# Dependencies Required
The Application only needs a linux environment for testing and the lpthreads should be working so make sure that you have libboost installed in your environment.
For that run the following command:
```
$ sudo apt-get install libboost-all-dev
```

# How to Run?
1. Clone this Repository
2. Go to the directory where you have cloned the repository and run the following commands:
```
$ g++ server.cpp -lpthread -o server
$ g++ client.cpp -lpthread -o client
```
3. Now Run the server using the following command:
```
$ ./server
```
4. You can run client using the following command:
```
$ ./client
```
5. For having Multiple clients you can perform Step-4 multiple times.
# Internal Working of the Project

# Learnings from the Project
Following are the things that I have learned during the course of the Project:
1. I am now able to clearly what threading is and what is it's importance in the large scale projects.
2. I have learned about the concept of Mutual-Exclusion (Mutex) in practical, I previously only had the theoretical knowledge of it.
3. I got to learn about many threading related functions that C/C++ has to offer , which I previously had no idea that they even exist.
4. 
# Video Demo

# References and Resources Used
