# mcast-tools
Multicast test tools

Origin of code

https://www.winsocketdotnetworkprogramming.com/winsock2programming/winsock2advancedmulticast9a.html

Example:

Run as receiver/client.
mcastws1 -b 192.168.1.2

Run as server/sender.
mcastws1 -b 192.168.1.1 -s



https://www.winsocketdotnetworkprogramming.com/winsock2programming/winsock2advancedmulticast9b.html

Example:

Run as receiver/client.
ip_sourcemcastv3 -b 192.168.1.1 -x

Run as sender/server.
ip_sourcemcastv3 -s -c -h 192.168.1.1 -n 7

## Stack
C++

## Responsible maintainer
- [Team LjudCore](mailto:team.ljudcore@sr.se)
