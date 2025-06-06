# cybersecuritytask-8
# VPN Exploration: Understanding Privacy and Secure Communication

## Objective
The primary objective of this assignment was to gain hands-on experience with Virtual Private Networks (VPNs) to understand their role in protecting online privacy and facilitating secure communication.

## Tools Used
* **Free VPN Client:** ProtonVPN Free Tier

## Deliverables
* A report detailing the VPN setup steps.
* A screenshot demonstrating the VPN connection status.

---

## My VPN Exploration Journey

### 1. Choosing and Setting Up the VPN

I chose **ProtonVPN Free Tier** for this assignment due to its strong reputation for user privacy and security features, even in its free version.

**Setup Steps:**

1.  **Account Creation:**
    * I navigated to the official ProtonVPN website (protonvpn.com).
    * I clicked on the "Get ProtonVPN Free" option and followed the prompts to create a free account. This involved providing my email address, setting a secure password, and completing an email verification step.

2.  **Client Download and Installation:**
    * After successfully creating my account, I was redirected to the download page.
    * I downloaded the **Windows** client application, as that is my operating system.
    * Once downloaded, I ran the installer file (`.exe`) and followed the on-screen instructions, accepting the terms and conditions to complete the installation process.

3.  **Connecting to a Server:**
    * Upon launching the ProtonVPN application, I was prompted to log in using my newly created credentials.
    * After logging in, I was presented with a map interface showing available free servers. I selected a server located in **Netherlands** as it was a free option and generally offers good connectivity.
    * I clicked the "Connect" button. After a brief connection process, the application indicated a successful connection with a green "Connected" status.

### 2. Verification and Browse Experience

**a) IP Address Verification:**

* **Before VPN:** I visited `whatismyipaddress.com` and noted my original IP address and location (e.g., `103.X.X.X` in Belagavi, Karnataka, India).
* **After VPN:** With ProtonVPN connected, I revisited `whatismyipaddress.com`. My IP address had successfully changed to a different one (e.g., `45.X.X.X`) with a reported location of **Amsterdam, North Holland, Netherlands**. This change clearly confirmed that the VPN was actively masking my true IP address and rerouting my traffic.

    * **Screenshot:** See `screenshots/vpn_connected_ip_changed.png`

**b) Encrypted Traffic Confirmation (using Wikipedia as an example):**

* While connected to ProtonVPN, I opened my web browser and navigated to **wikipedia.org**.
* I observed that the URL in the address bar started with `https://`, and a padlock icon was visible next to it. This confirmed that my connection to Wikipedia was encrypted using HTTPS, which is standard for secure websites.
* More importantly, the VPN itself ensures that *all* my internet traffic, regardless of the individual website's security (like HTTPS), is encapsulated and routed through an encrypted tunnel to the ProtonVPN server. This provides an overarching layer of security, preventing my ISP or any potential eavesdroppers on my local network (e.g., public Wi-Fi) from seeing my raw Browse data.

### 3. Disconnection and Comparison

* I disconnected from the ProtonVPN client. Immediately, when I re-checked `whatismyipaddress.com`, my IP address reverted to my original IP (`103.X.X.X`) in Belagavi, Karnataka, India.
* I performed some basic Browse tests. I noticed a **negligible** difference in Browse speed while the VPN was active compared to being disconnected, which was a positive observation for a free VPN tier. This slight overhead is generally acceptable for the significant privacy and security benefits.

### 4. Research on VPN Encryption and Privacy Features

My research into VPN technology highlighted several key aspects:

* **Encryption Protocols:** VPNs primarily rely on robust encryption protocols to secure data. Common protocols include:
    * **OpenVPN:** A highly secure and customizable open-source protocol. ProtonVPN primarily uses OpenVPN and WireGuard.
    * **WireGuard:** A newer, very efficient, and faster protocol that offers strong security.
    * These protocols establish a secure, encrypted "tunnel" between my device and the VPN server. All my internet traffic, including DNS requests, passes through this tunnel, making it unreadable to third parties, such as my Internet Service Provider (ISP) or anyone monitoring my network traffic. My data is transformed into ciphertext, protecting it from prying eyes.

* **Privacy Features:**
    * **No-Logs Policy:** ProtonVPN, like other reputable providers, adheres to a strict no-logs policy, meaning they do not record my online activities, IP addresses, or connection timestamps. This is foundational for true online privacy.
    * **Kill Switch:** This crucial feature automatically blocks all internet traffic if the VPN connection unexpectedly drops. This prevents my real IP address and unencrypted data from being inadvertently exposed.
    * **DNS Leak Protection:** Prevents my DNS requests (which resolve website names to IP addresses) from being handled by my ISP's DNS servers, thus preventing potential privacy leaks that could reveal my Browse habits.
    * **Secure Core (ProtonVPN specific):** For premium users, this feature routes traffic through multiple servers in privacy-friendly countries before leaving the network, adding an extra layer of security against advanced network attacks. (Though not used in free tier, it demonstrates advanced features).

### 5. Summary: VPN Benefits and Limitations

**Benefits of Using a VPN:**

1.  **Enhanced Online Privacy:** By masking my real IP address and encrypting my internet traffic, a VPN makes it significantly harder for websites, advertisers, and even my ISP to track my online activities, especially relevant when connected from Belagavi.
2.  **Data Security on Public Wi-Fi:** When connecting to unsecured public Wi-Fi networks (e.g., in cafes or airports), a VPN encrypts all data, protecting it from potential eavesdroppers or malicious actors on the same network.
3.  **Access to Geo-restricted Content:** By connecting to a server in a different country (e.g., Netherlands), I can potentially access online content and services that might otherwise be unavailable in my geographical region (India).
4.  **Circumventing Censorship:** In regions with internet censorship, VPNs can help bypass restrictions by creating an encrypted tunnel to a server outside the censored area.
5.  **Protection from Targeted Attacks:** Encrypted connections offer a layer of defense against certain types of cyberattacks that rely on intercepting unencrypted data.

**Limitations of VPNs:**

1.  **Potential for Speed Reduction:** The process of encrypting data and routing it through a remote server can sometimes introduce latency and slow down internet speeds. While negligible in my test, this can be more pronounced with distant servers or heavily loaded free VPNs.
2.  **Not a Universal Security Solution:** A VPN protects your connection, but it does not protect against all cyber threats. Malware, phishing scams, or weak passwords are still risks that require other security measures.
3.  **Trust in the VPN Provider:** Your data is routed through the VPN provider's servers. You must implicitly trust the provider's no-logs policy and security practices. Free VPNs, in particular, should be chosen with caution.
4.  **Limited Access to Free Features:** Free VPN tiers often come with limitations such as data caps (ProtonVPN free has no data cap but fewer servers), fewer server locations, or restricted speed.
5.  **Legality and Service Blocks:** While legal in most places, some countries restrict or ban VPN use. Additionally, some online services actively try to block VPN connections.

---

## Conclusion
This assignment provided valuable hands-on experience in setting up and utilizing a VPN with ProtonVPN Free Tier. It reinforced my understanding of how VPNs function as critical tools for safeguarding online privacy and securing communication in today's digital landscape, especially in locations like Belagavi where online privacy awareness is growing. While not a silver bullet, a reputable VPN is an indispensable part of a comprehensive online security strategy.

## Screenshots

* [**VPN Connected Status:**](screenshots/vpn_connected.png)
    * *Description:* A screenshot from the ProtonVPN application showing a successful connection to a server.

* [**IP Address Change Verification:**](screenshots/vpn_connected_ip_changed.png)
    * *Description:* A screenshot from `whatismyipaddress.com` demonstrating the altered IP address and location (matching the VPN server) while the VPN was active.
