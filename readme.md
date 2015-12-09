Creates a server at localhost with one service called "is_even" that receives a number and prints out if it's even or not.

Run as separate processes (e.g. separate terminal tabs) and in this order:
  * `jython ~/workspace/training/Jython/xml-rcp/server.py` 
  * `jython ~/workspace/training/Jython/xml-rcp/client.py` 

You should see:

* server:

 ```
Listening on port 8000...
127.0.0.1 - - [09/Dec/2015 14:12:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [09/Dec/2015 14:12:13] "POST / HTTP/1.1" 200 -
```

* client:
 ```
 3 is even: False
 10 is even: True
```
