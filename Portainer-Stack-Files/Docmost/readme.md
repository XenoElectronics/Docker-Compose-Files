The content of the yaml file should be copied into the Portainer stack.

***

Here is the official guide.

https://docmost.com/docs/installation/

I have changed the Compose file so that you can simply copy it into the stack.

It is important to replace the APP_Secret. To do this, run this script in the terminal:

openssl rand -hex 32

It should display a 32 character code. This is then inserted where #REPLACE_WITH_LONG_SECRET is.

Docmost should then run without any problems.