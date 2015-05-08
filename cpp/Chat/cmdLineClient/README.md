This demo is a C++ commandline client for the [ZeroC Chat Demo](https://zeroc.com/chat/index.html). This demo connects to a single chat room, allowing you to chat with other chat room participants.

By default, the demo connects throught a WebSocket proxy hosted on zeroc.com to a chat server hosted on demo.zeroc.com.

You may run either the Glacier2 client (`chatgl2client`) or the polling client (`chatpollclient`), as well as any username or password to connect.


If you wish to run your own server you can specify a custom configuration file when launching the client:

```
$ chatgl2client --Ice.Config=config.client
```