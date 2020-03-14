# cli_chat
A command line tool to communicate on a network via the terminal or command prompt.

# setup
The program is a client-server model setu using the socket module in python. The server instance is created by binding its socket to the host machine and a port (above 1024 to avoid collision). The same address is used in the client script to access the server instance. The script can be executed on a single machine and can also be accessed over the network when the server ip address is set to __0.0.0.0__.

## credit:
- https://www.journaldev.com/15906/python-socket-programming-server-client
