The content of the yaml file should be copied into the Portainer stack.

You have to generate a Token for these four lines:

JWT_SECRET:
ADMIN_JWT_SECRET:
API_TOKEN_SALT:
TRANSFER_TOKEN_SALT:

https://it-tools.tech/token-generator?length=32

Attention: if the container is running and you open it in Portainer, it uses localhost even if you have not specified this in the environment.


You only have to enter the IP address where the container is installed.