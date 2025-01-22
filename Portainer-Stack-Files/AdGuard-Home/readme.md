The content of the yaml file should be copied into the Portainer stack.

All you need to change is the timezone.

***

There is no port in the stack, believe me this does not cause any problems. Adguard uses the host ports.

If you roll out the stack, you can access AdGuard with port 3000 to configure it.

It then wants to use port 80 for the web interface, which should be changed to port 9080, for example.

Port 80 is used by too many services. But it is up to you which port AdGuard should use.

In the router, the IP of the server where AdGuard is running must be static and the IP of the AdGuard server must be entered as the DNS server.

If you want to use Adguard with Nginx Proxy Manager to add local server domains, you have to go to Adquard under Filters/DNS rewrites and then to ADD DNS Rewrite.

There you must then enter the domain with: *.DOMAIN

and then enter the IP of the reverse proxy.