# tao-of-dao
pedantic dao example

This repo contains a dao implementatio using modern java techniques.

It is pedantic, because:

. It does not need or support annotaions in its API, because we thick reflection is overused.
. When we use reflection, we do that at build time, not at compile time. That is: just once in the lifetime of the code.
. We use naming conventions.

