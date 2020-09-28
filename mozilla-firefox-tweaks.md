---
description: Get all the latest tweaks available in Mozilla Firefox
---

# Mozilla Firefox Tweaks

## Set up DNS-over-HTTPS in Mozilla Firefox

### **Configuration Panel**

* \(Default\) Set Cloudfare.
* Set a custom DNS resolver.

Choose any of the following to set DNS resolver:

 Select **Enable DNS over HTTPS**.

 In menu, navigate to **Tools** &gt; **Preferences** &gt; **General** &gt; **Settings** &gt; **Network Settings.**

### Preferences Menu

*  Type **1.1.1.1** for **Cloudfare**.
*  Type **8.8.8.8** for **Google**.

 \(Optional\). In the search area, type **network.ttr.bootstrapAddress** to set up IP address.

*  The default Cloudfare URI is [https://mozilla.cloudflare-dns.com/dns-query](https://mozilla.cloudflare-dns.com/dns-query)

 In the search area, type **network.ttr.uri** to set the domain name of the DNS resolver.

*  **2:**  Turns on DoH and keeps the regular DNS only as a backup.
*  **3:** Turns on DoH with no regular DNS support.

 In the search area, type **network.ttr.mode** and set any of the following values:

 Type **about:config** in the URL bar.

