# SCAM - Simple Chat And Messaging Protocol

SCAM is a web protocol that was designed to be easy to understand and use.
It focuses on transporting messages to and from a server based chatroom that is accessible through a url.

SCAM messages are not encrypted by default, but encrypted messages are supported by the protocol.

## URI Formatting

URIs that point to a SCAM chatroom are very easy to understand and parse.
The default layout of a URI follows a HTTP URL layout. 

In order to make the following URI valid, replace [HOST] with the hostname, DNS address or IP of the server.
Also replace the [CHAT] part witht the name of the chatroom you are trying to join.

    scam://[HOST]/[CHAT]

## SCAM examples

To get started with SCAM, we would recommend that you download a SCAM server and a SCAM client.
We have created some examples for you:

### [SCAM Server](https://github.com/9hax/scam-server)

For your convenience, we have created a SCAM Server that is implemented in Python3.
It is designed with customization in mind.

### [SCAM Client](https://github.com/9hax/scam-client/)

Here is a SCAM Client, written in Java.
