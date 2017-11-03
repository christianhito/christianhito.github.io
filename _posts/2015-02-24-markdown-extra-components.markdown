HOW TO BLOCK FACEBOOK ACCESS WIHTIN YOUR LAN


In order to bloack facebook access within your lan network, you will need to configure pfsense as your gateway and firewall. There is a good guide on the pfsense's website which might be very helpful in order to help one for the installion and initial setups, i will try to make a post in the nearest future regarding pfsense's installation and intial configurations. 

There is a package called PFblocker-ng in pfsense, this package is the coolest thing in the firewall's blocking perspective. 

Talking about how to block facebook or anyother website, it going to be a brutal approach by timing out the IP requests from your lan to the public network (internet) and vise versa. in other to collect all the possible IPs of a  website, in our case facebook's IPs, there is one thing called autonomous system number (ASN). techopedia.com defines that number asP a unique number that's available globally to identify an autonomous system and which enables that system to exchange exterior routing information with other neighboring autonomous systems. The number of autonomous system numbers is limited.

The faceboo asn is described on the following link https://www.facebook.com/peering/ and could also be found on the https://www.peeringdb.com/ webiste (you can find anyother website asn on the website too :) ).

