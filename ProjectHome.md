A really simple php proxy that 'just works'.

This project was put together as a simple system that could be taken and extended to ones needs.  I was largely disappointed that none of the other systems seemed to handle POST,COOKIE and SESSION information well - if at all!

The whole system was put together in about 2 hours - and just works!

The code is intentionally bare bones and easy to read.  This will enable you to get on with using the proxy for what you actually want!  In my case to transparently sniff the data going too & from the browser and a site so that I can extract and log information to a database!

To use the proxy effectively you will require a server with .htaccess and mod\_rewrite support.

### INSTALL ###

1. Preferably use the proxy on it's own domain  e.g. http://proxy.xyz.com/

2. Rename htaccess.txt to .htaccess and install on your server.

3. Download the proxy script and install it in the root web folder as 'index.php'.

4. Edit the script and adjust the target domain name you would like to scrape!

Done!

