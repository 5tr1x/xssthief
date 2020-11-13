<h2>Description</h2>

Creates xss payloads and starts http server to collect cookies

<h2>Options</h2>

```
usage: xssthief [-h] [-o] lhost

creates xss payloads and starts http server to collect cookies

positional arguments:
  lhost             ip address of listening host

optional arguments:
  -h, --help        show this help message and exit
  -o, --obfuscated  create obfuscated payload

xssthief 10.10.10.50
xssthief 10.10.10.50 --obfuscated
```
