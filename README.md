# dispatch\_router\_examples
Examples of setting up and running the QPID Dispatch Router

01\_hello\_world

Build and install the router from source, send 5 messages through it from a Python sender to a Python receiver.



02\_4\_mesh

Start 4 routers in a mesh -- i.e. in a completely connected network. Use one sender and a multicast address so that each of 4 receivers gets every one of the sender's messages.


