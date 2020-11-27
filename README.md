# ITT440-Lab5
Socket Programming Using Python 

*Copying files from client to the server for storage*

Files:
- serverStore.py (for server side)
- clientStore.py (for client side)

Steps:
1. Run *serverStore.py* on the server host
2. Run *clientStore.py* followed by the server ip address on the client host
3. Input the name of the file to be copied to the server including its extension
4. Done

Troubleshooting:
- Make sure the IP address of the server is correct when connecting to it from the client side.
- The filename that is entered during step 3 must exist in the same directory of *clientStore.py*.
- The characters limit of file that can be copied is 99999. Anything bigger will cause the server to stop copying the rest of the file after reaching the limit.
