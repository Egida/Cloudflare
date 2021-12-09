### ☁️ Cloudflare Firewall Rules To Prevent DDOS Attacks ☁️

Not recommend for sites with a large target range inside Asia

## ☁️ Firewall Rules ☁️

Rule Name | File Name | Action | What For
---- | ---- | ---- | ----
General | [rules.ssl](./rules.ssl) | Manual ADD | Peformance, User Experience, DDOS Protection, Crawlers<br>
Countries | [common-country.rules](./common-country.rules) | Block | Only Allow Country's Who Wont Pass Much Malicous Traffic.<br>
ASN List | [bad-asn.rules](./bad-asn.rules) | Block | ASN List Of Most Known Proxyscraping Sites.<br>
Threat Score | [threatscore.rules](./threatscore.rules) | Block | Block Bad Threats Flagged By Cloudflare<br>
Request Method | [request-method.rules](./request-method.rules) | Block | Block POST & HEAD Request's Only Allow GET Request's Unless Needed.<br>

## ☁️ How To Basic ☁️
![](https://media.discordapp.net/attachments/819747919581675530/829677841292460042/unknown.png) 
![](https://media.discordapp.net/attachments/819747919581675530/829678093706592276/unknown.png) 
![](https://media.discordapp.net/attachments/819747919581675530/829678478278000650/unknown.png) 
![](https://media.discordapp.net/attachments/819747919581675530/829678903131897906/unknown.png) 


```
I made these firewall rules a few months back because people were paying upwards of $100+??
Say it probably pissed a-lot of people off who profited off that shit however I don't have the resources to update these rules or nor ever plan to
The rules most likely still work just not as well as they used to or just as well not sure nor do I really care its not worth my attention
Not going into detail on how these "Cloudflare-bypasses" work but needless to say there not really bypasses just a bit of traffic (150-2k) requests using public scraped proxies
Hence the rather large ASN list, if you have the resources and time of rotating proxies needless to say you just need to update the ASN's of new proxy services
I may update them in the future for another project to come but I highly doubt I will being using Cloudflare.

Anyways I hope they help your services from big scary hax0rs.

Sincerly,
pwnkp
