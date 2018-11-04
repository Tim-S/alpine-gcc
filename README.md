# alpine-gcc
A small container for compiling c++ programs

## Usage Example:
```shell
docker run --rm -v ${PWD}:/tmp schneidertim/alpine-gcc g++ -std=c++0x "/tmp/src/UDPServer.cpp" -o /tmp/UDPServer
```
