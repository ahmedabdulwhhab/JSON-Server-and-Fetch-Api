# JSON-Server-and-Fetch-Api
quoted from 
https://gist.github.com/nitaku/10d0662536f37a087e1b
comment 
mfickett commented on Jul 14, 2020

To be able to understand the basics of requesting data from server using
fetch API (Method Get and POST) or XMLRequest,you have to implement a 
server, which have some database, then you request data from it.

The easiest way to implement server is to use Python.
the code is free on the internet.
https://gist.github.com/nitaku/10d0662536f37a087e1b
comment 
mfickett commented on Jul 14, 2020
with some modifications.


# In Rev003
assuming Linux Machine has IP address 192.168.1.11
my aim was to understand the fetch GET and POST using a server using json format.

so you can find HTML file for javascript

and python file for server with output json format
the HTML code is existed under json_REST_API015.html
the following link is an explanation for it in arabic language
https://youtu.be/NRkCY-fe-Ok


# In Rev004
assuming Linux Machine has IP address 192.168.1.11
to request time from server 
curl http://192.168.1.11:8082/time
or 
use browser
http://192.168.1.11:8082/time

to request date from server 
curl http://192.168.1.11:8082/date
or 
use browser
http://192.168.1.11:8082/date


to get json data
use
curl http://192.168.1.11:8082
or 
use browser
http://192.168.1.11:8082


