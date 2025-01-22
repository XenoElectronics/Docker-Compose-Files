The content of the yaml file should be copied into the Portainer stack.

***

If you have set up HTTPS with a reverse proxy, Nextcloud does not want to allow the domain. You can add this in the file under _data/config/config.php.

Search for the IP address that is stored for http. It looks like this:

> 0 => '192.168.0.0' ,

Then simply enter the following below it

> 1 => 'Domain',