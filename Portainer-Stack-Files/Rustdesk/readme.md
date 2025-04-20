The content of the yaml file should be copied into the Portainer stack.

***

It is important to enter the IP of the Docker host and the public key of Rustdesk in the Rustdesk Desktop app.

The Key can be found under /var/lib/docker/volumes/rustdesk_hbbs/_data/id_ed25519.pub

the public key can then be read with the command:

```
cat id_ed25519.pub
```