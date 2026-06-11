# Using-WireGuard-v15-and-Wg-Easy-with-Caddy-SSL
This is an example on how to use WireGuard Easy with Caddy, to access it on an HTTPS domain (e.g. https://wg-easy.mywebsite.com).

Edit the variables marked with ⚠️ and save the files. Run "docker-compose up -d" in the same directory. Caddy generates SSL certificates and automtes renewal.  

To work, you need a domain and to configure DNS settings with your provider (for example mywebsite.com and then wg-easy.mywebsite.com) Ports 80, 443 and 51820 must be available through your router and various firewalls.

Thanks to the heavy lifting by the folks at Wireguard and Caddy for making this possible.

I've found this to be the easiest and tidiest way to get your own VPN running on the clearnet, to build out your own services as you wish.

Cheers, Skurrrrr
