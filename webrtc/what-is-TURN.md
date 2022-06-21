# What is TURN?

> Some routers using NAT employ a restriction called 'Symmetric NAT'. This means the router will only accept connections from peers you've previously connected to.
>
> Traversal Using Relays around NAT (TURN) is meant to bypass the Symmetric NAT restriction by opening a connection with a TURN server and relaying all information through that server. You would create a connection with a TURN server and tell all peers to send packets to the server which will then be forwarded to you. This obviously comes with some overhead so it is only used if there are no other alternatives.

## Sources
* https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API/Protocols#turn
* https://en.wikipedia.org/wiki/Traversal_Using_Relays_around_NAT
