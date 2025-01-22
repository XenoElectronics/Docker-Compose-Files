The content of the yaml file should be copied into the Portainer stack.

***

Official Guide: https://docs.paperless-ngx.com/setup/#docker

You cannot log in after deploying. You have to create a super user for this, they have a script on the website above. Should be section 6.

In the website container you have to enter this command.

> python3 manage.py createsuperuser

To do this, you can simply open the terminal of the Docker container in Portainer and copy it in.