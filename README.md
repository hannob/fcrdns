# fcrdns
Command line Forward-confirmed reverse DNS (FCrDNS) check written in Python

This script implements a simple FCrDNS check. More info:
* https://en.wikipedia.org/wiki/Forward-confirmed_reverse_DNS

Usage:
```
fcrdns [ip]
```

The script will return 0 and output nothing if everything's ok and return 1
and output an error message if the FCrDNS check fails.

author
======

[Hanno Böck](https://hboeck.de/)
