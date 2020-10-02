---
description: >-
  Create and use your own cloud environment. Install and configure ownCloud X
  Server for set up. Use ownCloud Desktop Client for usage.
---

# Set up OwnCloud

## ownCloud X Server Installation

1. Go to the [ownCloud](https://owncloud.com/download/) installation page.
2. Sign up and download the ownCloud OVA file.
3. Open Oracle VM VirtualBox and navigate to **File** &gt; **Import Appliance**.
4. Browse and select the downloaded OVA file.
5. \(Optional\) Modify the default settings.
6. Accept the software license and click **Import**.

## ownCloud X Server Configuration

1. Open Oracle VM VirtualBox and start the ownCloud installed appliance.

   **Tip**: Server boot might take up to five seconds.

2. Select your desired language.
3. Configure timezone, system locale, and keyboard layout.

   **Tip**: To configure automatically, enter the city name.

4. Configure the network settings.
5. Select **Obtain IP address automatically \(DHCP\)** and use the default settings.
6. Configure the domain settings.
7. Select **Manage users and permissions directly on this system**.
8. Enter your account information: company name, email address, and password.

   **Tip**: Password must consist of minimum eight ASCII characters.

9. Configure the host settings: use existing values or configure manually.
10. Select **Update system after setup** and then click **CONFIGURE SYSTEM**.

    **Step Result**: Oracle VM VirtualBox restarts and displays the IP address \([https://192.168.0.102\](https://192.168.0.102\)\) to access ownCloud server through a web browser.

11. Open a web browser and enter the IP address.
12. To receive the license file, add your email address.
13. Upload the received license file and complete the activation.

## User Account

1. Go to the [ownCloud server univention portal](https://192.168.0.102) page.
2. Navigate to **Administration &gt; System and domain settings &gt; Users &gt; ADD** and enter new user details.

   **Tip**: To ensure that users create their own password, choose **User has to change password on next login**.

3. Click **CREATE USER**.

## ownCloud Desktop Client Setup

1. Go to the [ownCloud](https://owncloud.com/download/) installation page.
2. Navigate to **ownCloud Desktop Clients &gt; ownCloud Linux Client** and download the desktop client.
3. Select an operating system and follow the instructions.
4. After the installation, open the client.
5. Enter the ownCloud server address that you received from your administrator.

   **Note**: Append **/owncloud** after the server IP address.

6. Trust the certificate and enter the user account credentials.
7. Setup and synchronize the local folder with the server.
8. Click **Connect**.

