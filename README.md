# webserv (thervieu/hcanon)

(42 subject) Create a HTTP server from scratch!

## Table of Content

* [Technologies](#technologies)
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Utility](#utility)
* [Contributing](#contributing)

## Technologies

Project is created with:
* clang++ 13.0.0

## Description

The first aim of the project is getting to know how to use sockets in C and the functions associated (bind, listen, accept, select, recv, send...).\
The second one is learning what HTTP is and how it works. It also means to learn all about the syntax and conventions associated with HTTP: error codes, headers, responses, requests, etc...

## Installation

Just pull the project !

## Usage

Classic 42 Makefile:
````sh
make		#compiles everything and create woody_woodpacker binary
make clean	#removes all the .o files
make fclean	#removes all the .o files and the "woody_woodpacker" binary
make re		#cleans everything in the project and compiles everything again
````

Specific to the project:
````sh
./webserv [path to the .conf file] #launch the server(s) on the port(s) indicated on the configuration file
````

## Utility

Very useful

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
