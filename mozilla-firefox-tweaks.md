---
description: Get all the latest tweaks available in Mozilla Firefox
---

# Mozilla Firefox Tweaks

## Set up DNS-over-HTTPS in Mozilla Firefox

### **Preferences Menu**

1. In menu, navigate to **Tools** &gt; **Preferences** &gt; **General** &gt; **Settings** &gt; **Network Settings.**
2. Select **Enable DNS over HTTPS**.
3. Choose any of the following to set DNS resolver:

   `(Default) Set Cloudfare.`

   `Set a custom DNS resolver.`

### Configuration Panel

1. Type **about:config** in the URL bar.
2. In the search area, type **network.ttr.mode** and set any of the following values:

   **`2:`**`Turns on DoH and keeps the regular DNS only as a backup.`

   **`3:`** `Turns on DoH with no regular DNS support.`

3. In the search area, type **network.ttr.uri** to set the domain name of the DNS resolver.
   * The default Cloudfare URI is [https://mozilla.cloudflare-dns.com/dns-query](https://mozilla.cloudflare-dns.com/dns-query)
4. \(Optional\). In the search area, type **network.ttr.bootstrapAddress** to set up IP address.

   **Cloudfare: 1.1.1.1**

   **Google: 8.8.8.8**



