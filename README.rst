debian-efnet
============

Welcome to the official 'home page'. This github repository is maintained
by the debian-efnet channel ops.

Here you will find, amongst other things, our idea of best practice
solutions to common questions asked by users.

Best Practice
-------------

Identd
......

It is our opinion that Identd has been redundant for at least thirty years
and is completely unnecessary in 2011. In fact, it was completely
unnecessary in 2000.

Running an entire daemon just to remove the ~ prefix from your ircname not
only requires additional administration overhead to set up the service, it
opens your server up to one more potential service to get hacked. 

Without Identd your IRC experience will be just as good, if not better
without an ident daemon. IRC Bouncers and eggdrops do *not* require identd
to authenticate.