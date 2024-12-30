# Detailed Documentation for the project Web Server From Stratch in C

## Introduction

This project is a web server that can be used to host a website. It is written in C and uses the libeom library for its implementation. The project is divided into three main sections: the Networking, Data Structures, and Systems. The Networking section contains the Nodes, Client, and Server, which are used to create a client and server. The Data Structures section contains the Dictionary, LinkedList, and Queue, which are used to store data. The Systems section contains the ThreadPool, which is used to create threads. The project also includes the main.c file, which is used to compile the project and run the server.

## Networking

The Networking section contains the Nodes, Client, and Server, which are used to create a client and server. The Nodes section contains the PeerToPeer, which is used to create a client and server. The Client section contains the Client, which is used to make requests to a server. The Server section contains the Server, which is used to handle requests from clients.

### PeerToPeer

The PeerToPeer object is intended as a wrapper for a node with client and server capacities. The object requires the client and server functionalities be defined by the user.

### Client

The Client object is used to make requests to a server. The object requires the request method to be defined by the user.

### Server

The Server object is used to handle requests from clients. The object requires the launch method to be defined by the user.

## Data Structures

The Data Structures section contains the Dictionary, LinkedList, and Queue, which are used to store data. The Dictionary object is used to store key-value pairs. The LinkedList object is used to store a list of data in a linear fashion. The Queue object is used to store a list of data in a first-in-first-out fashion.

### Dictionary

The Dictionary object is used to store key-value pairs. The object requires the compare function to be defined by the user.

### LinkedList

The LinkedList object is used to store a list of data in a linear fashion. The object requires the insert and remove methods to be defined by the user.

### Queue

The Queue object is used to store a list of data in a first-in-first-out fashion. The object requires the push and pop methods to be defined by the user.

## Systems

The Systems section contains the ThreadPool, which is used to create threads. The ThreadPool object is used to create a provided number of threads awaiting work to be added to a queue. The object requires the add_work method to be defined by the user.

### ThreadPool

The ThreadPool object is used to create a provided number of threads awaiting work to be added to a queue. The object requires the add_work method to be defined by the user.
