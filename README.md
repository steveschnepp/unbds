# unbds

This is a micro NBD server.

Its main design is "small". That means no extensive dependencies, no extensive features.
The goal was to have the minimal server on an embedded NAS with 64MiB RAM and a 200MHz CPU.

## Limits

It is only single-threaded, and programmed in a very naive way.
