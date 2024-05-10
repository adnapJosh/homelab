This took me a few days of failed configurations to finally figure out.  

# **PiVPN Attempts**
Intially I had used this [tutorial](https://www.youtube.com/watch?v=V9sWhnYQvpE) from [Homelab Tim](https://www.youtube.com/@HomelabTim), which used [PiVPN](https://www.pivpn.io/) as a method of adding Wireguard to an Ubuntu-Server LXC.
Unfortunately I wasn't able to correctly conffigure it after multiple attempts using this method.
I'm still unsure what the exact problem was that caused my connections to not link, but I belived it had to do with either an IP mismatch between the peer and interface.
(Although I made sure to always make sure they were configured correctly)

While these attempts ultimately failed, I was able to learn a fair bit of the beginner Linux commands during my troubleshooting. 
Which helped me during my next attempts.

# **Wireguard Roadwarrior Attempt**
This attempt uses this [tutorial](https://www.youtube.com/watch?v=er01qTRwqEo) from [homelabd](https://www.youtube.com/@homelabd), which uses this [github repository](https://github.com/Nyr/wireguard-install) from a user called Nyr.
This opted to use Nyr's _wget_ script to install wireguard and run through an installation wizard to assist with setup.
I found this to be a simpler method of configuring a fresh wireguard install and peering it to a device. 

# **Notes**  
* I found that by using a DDNS to link my dynamic ip from my ISP makes the maintenance of switching the endpoint IP every few weeks much simpler. I use [DuckDNS](https://www.duckdns.org/).
* I have also used a different port number as I have heard it's a good security practice to follow.
