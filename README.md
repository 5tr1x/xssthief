<h2>Description</h2>

Creates xss payloads and starts http server to collect cookies

<h2>Options</h2>

```
usage: xssthief [-h] [-e] [-i] [-o] lhost

creates xss payloads and starts http server to capture responses and collect cookies

positional arguments:
  lhost             ip address of listening host

optional arguments:
  -h, --help        show this help message and exit
  -e, --error       create error payload
  -i, --image       create image payload
  -o, --obfuscated  create obfuscated payload

xssthief --error 10.10.10.50
xssthief --image 10.10.10.50
xssthief --obfuscated 10.10.10.50
```
