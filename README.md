# Chat-room-python
This is a basic chat room where clients can connect via client script and a host can create a room server
and allow multiple clients to connect to it using a client-side script. 
The code uses the concept of sockets and threading.

Using the Project--

    Both the server and client script can then be run
    from the Command prompt or terminal by simply typing 
      "python chat_server.py  " or "python client.py  ".

Other usefull information to setup--

  1. This server can be set up on a local area network by choosing any on computer to be a server node, 
  2.  using that computer’s private IP address as the server IP address.
        For example, if a local area network has a set of private IP addresses assigned ranging from 192.168.1.2 to 192.168.1.100, 
        then any computer from these 99 nodes can act as a server,and the remaining nodes may connect to the server node by using 
        the server’s private IP address. 
  NOTE--  Care must be taken to choose a port that is currently not in usage. For example, port 22 is default for ssh,
        and port 80 is default for HTTP protocols. So these two ports shouldnt be used or reconfigured to make them free for usage.
