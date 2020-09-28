---
description: The most annoying task in the easiest way possible.
---

# Inverse Lattice Help

## Set up DNS-over-HTTPS in Mozilla Firefox

### Preferences Menu

 In menu, navigate to **Tools** &gt; **Preferences** &gt; **General** &gt; **Settings** &gt; **Network Settings.**

 Select **Enable DNS over HTTPS**.

Choose any of the following to set DNS resolver:

* \(Default\) Set Cloudfare.
* Set a custom DNS resolver.

### **Configuration Panel**

 Type **about:config** in the URL bar.

 In the search area, type **network.ttr.mode** and set any of the following values:

*  **2:**  Turns on DoH and keeps the regular DNS only as a backup.
*  **3:** Turns on DoH with no regular DNS support.

 In the search area, type **network.ttr.uri** to set the domain name of the DNS resolver.

*  The default Cloudfare URI is [https://mozilla.cloudflare-dns.com/dns-query](https://mozilla.cloudflare-dns.com/dns-query)

 \(Optional\). In the search area, type **network.ttr.bootstrapAddress** to set up IP address.

*  Type **1.1.1.1** for **Cloudfare**.
*  Type **8.8.8.8** for **Google**.

