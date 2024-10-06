# GoodBots

精心策划的IP地址列表/良好机器人和爬虫程序的白名单。包括GoogleBot、BingBot、DuckDuckBot等。

所有IP列表都在 [CIDR-Notation](https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing) 中，可以用作Web服务器防火墙中的白名单或速率限制的例外。

使用 [all.ips](all.ips) 列表或在 [iplists/](iplists/) /目录中找到的特定服务的IP地址列表。

这些列表每天通过预定的GitHub Action更新。

<!-- TODO: Better Readme -->
  
```
.
├── all.ips 
│   Combined List of all IP addresses found in iplists/
│
└── iplists/
    │
    ├── ahrefsbot.ips
    │   IP-Addresses used by the AhrefsBot Crawler
    │   
    ├── applebot.ips
    │   Apple doesn't publish its "AppleBot" Crawler IPs, so this list includes all Apple IPs →TODO: Find better solution
    │   
    ├── betteruptimebot.ips
    │   IP-Addesses used by the BetterUptime Bot
    │   
    ├── bingbot.ips
    │   IP-Addesses used by the Bing Crawler
    │   
    ├── bunnycdn.ips
    │   IP-Addesses used by the bunny.net CDN
    │   
    ├── cloudflare.ips
    │   IP-Addesses used by the Cloudflare CDN
    │   
    ├── duckduckbot.ips
    │   IP-Addesses used by the DuckDuckGo Crawler
    │   
    ├── facebookbot.ips
    │   IP-Addesses used by the Facebook Link-Preview Bot
    │   
    ├── freshpingbot.ips
    │   IP-Addesses used by the Freshping Bot
    │   
    ├── googlebot.ips
    │   IP-Addesses used by the Google Crawler
    │   
    ├── imagekit.ips
    │   IP-Addesses used by the Imagekit.io Image Proxy
    │   
    ├── imgix.ips
    │   IP-Addesses used by the Imgix Image Proxy
    │   
    ├── internal.ips
    │   Internal IP-Addresses
    │   
    ├── marginalia.ips
    │   IP-Addresses used by the Marginalia Search Crawler
    │   
    ├── mojeekbot.ips
    │   IP-Addesses used by the Mojeek Crawler
    │   
    ├── molliewebhook.ips
    │   IP-Addesses used by Mollie to send out Webhooks
    │   
    ├── outageowl.ips
    │   IP-Addesses used by the Outage Owl Bot
    │   
    ├── pingdombot.ips
    │   IP-Addesses used by the Pingdom Bot
    │   
    ├── rssapi.ips
    │   IP-Addesses used by the RSSAPI.net Feed parser
    │   
    ├── stripewebhook.ips
    │   IP-Addesses used by Stripe to send out Webhooks
    │   
    ├── telegrambot.ips
    │   IP-Addesses used by the Telegram Link-Preview Bot
    │   
    ├── twitterbot.ips
    │   IP-Addesses used by the Twitter Link-Preview Bot
    │
    ├── uptimerobot.ips
    │   IP-Addesses used by UptimeRobot.com
    │
    └── webpagetestbot.ips 
        IP-Addesses used by Webpagetest.org
        
```
