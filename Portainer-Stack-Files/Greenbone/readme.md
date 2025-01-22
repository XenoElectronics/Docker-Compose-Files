The content of the yaml file should be copied into the Portainer stack.

Official guide:

https://greenbone.github.io/docs/latest/22.4/container/index.html#docker-compose-file

***

When Greenbone is installed it wants login credentials. The default credentials are:

Standard User

>User: admin

>Password: admin

I would put the scanner in a separate VM with a lot of resources. It makes a lot of containers and needs lot of CPU power and RAM.

If the Greenbone containers are terminated in any form. Be it a reboot or shutdown of the server where Docker is running. You can no longer access the web interface.

You then have have to select the stack in Portainer and restart all containers.

To prevent this, you can edit the Compose file or set the restart policy to Always in the containers.