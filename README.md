# pnt
**pnt** is a generic pentesting-oriented networking tool implemented in Python.

## What it can do
- connect to / communicate with servers using various protocols (raw TCP sockets, HTTP, POP / IMAP, SMTP, IDENT etc.)
- create custom HTTP requests (including XML RPC)
- send / retrieve email to / from SMTP / POP3 servers
- push / pull files using a custom (very basic) protocol (fpush)
etc.

## Misc features
- connect through SOCKS4 proxies
- retrieve robots.txt
- check for the shellshock vulnerability
- inject <?php...?> command-running requests in the webserver log
- brute-force SSH authentication using a list of certificates (testing for bashbug)
etc.

## Feedback
This code is released mostly to serve as a source code example for networking in Python; please direct feedback to vtopan/gmail.
