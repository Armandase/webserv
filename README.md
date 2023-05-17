
# webserv

42's webserv project

This is a minimal web server in c++ which handle GET, POST and DELETE request.

It use epoll as socket manager and the socket are in SOCK_STREAM mode (tcp)


### Installation

install and compile it 

```bash
  git clone https://github.com/Armandase/webserv
  cd webserv
  make
```
    
### Usage

Start the server
```c++
./webserv [configuration file]
```
