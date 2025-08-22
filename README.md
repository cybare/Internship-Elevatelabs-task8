# Internship-Elevatelabs-task8

## Task 8 :

Identify and Remove Suspicious Browser Extensions

### Objective: 

Understand the role of VPNs in protecting privacy and secure communication.
### Tools:

Free VPN client (ProtonVPN free tier, Windscribe free)

### Deliverables:  

Report describing VPN setup steps and connection status screenshot

### Soltion:

##### Step 1 :- Windscribe free choosen as a reputable free VPN service and sign up is done. 

#### Step 2 :- Download and install the VPN client.

#### Step 3 :- Connect to a VPN server (choose any location).

![locationset](Screenshot/Locationset.png)

#### Step 4 :- Verify my IP address has changed

 ##### IP Address before VPN connection 

![Ipaddressbeforevpn](Screenshot/Ipaddressbeforevpn.png)

##### IP Address after VPN connection

![ipaddressaftervpn](Screenshot/ipaddressaftervpn.png)

##### Use what is my IP address

![whatismyip](Screenshot/whatismyip.png)

#### Step 5:- Research VPN encryption and privacy features.

 ##### 1. Encryption

###### AES-256 (Advanced Encryption Standard)

- Most modern VPNs use AES-256-bit encryption, considered military-grade.

- It protects your data by scrambling it into unreadable ciphertext.

- Even with brute-force attacks, it would take billions of years to crack.

###### ChaCha20 Encryption (modern alternative)

- Used by some VPNs with the WireGuard protocol.

- Faster and more lightweight than AES, suitable for mobile devices.

##### 2. VPN Protocols (Tunnels for Encryption)

###### OpenVPN

- Open-source, highly secure, supports AES-256 encryption.

- Works on UDP (faster) or TCP (more reliable).

###### WireGuard

- Modern, lightweight, faster, and uses ChaCha20 encryption.

_ Strong forward secrecy (new keys for each session).

###### IKEv2/IPSec

- Stable and great for mobile networks.

- Automatically reconnects if the connection drops.

##### 3. Privacy Features

###### No-Logs Policy

- A good VPN provider does not record your browsing history, IP addresses, or activity.

- Some providers have been audited to prove this.

###### IP Masking

- VPN replaces your real IP address with one from the VPN server.

- Hides your location and identity from websites.

###### DNS Leak Protection

- Prevents your ISP or third parties from seeing your DNS requests.

- Without it, even if traffic is encrypted, your DNS lookups might expose visited websites.

###### Kill Switch

- If the VPN connection drops, internet access is blocked automatically.

-Prevents accidental exposure of your real IP.

###### Split Tunneling

- Lets you choose which apps use the VPN and which use the normal internet.

- Useful for streaming or banking.
 
#### Step 6:- Write a summary on VPN benefits and limitations

##### Benefits of VPNs

1) Data Encryption – VPNs encrypt internet traffic (commonly with AES-256 or ChaCha20), protecting sensitive information from hackers and eavesdroppers, especially on public Wi-Fi.

2) Privacy Protection – By masking your real IP address, VPNs prevent ISPs, websites, and third parties from easily tracking your online activities.

3) Geo-Unblocking – VPNs allow access to region-restricted content (e.g., streaming services or blocked websites).

4) Bypass Censorship – In restricted environments, VPNs provide a secure tunnel to the open internet.

5) Secure Connections – VPN protocols like OpenVPN and WireGuard add layers of authentication and forward secrecy, strengthening communication security.

##### Limitations of VPNs

1) Not Foolproof Privacy – While VPNs hide your IP, websites you log into (e.g., Gmail, Facebook) can still identify you.

2) Reduced Speed – Encryption and routing traffic through remote servers can slow down browsing or downloads.

3) No Malware Protection – VPNs don’t block viruses, phishing, or malicious downloads unless bundled with security tools.

4) Trust in Provider – Users must trust that the VPN service does not log or misuse their data. Free VPNs are especially risky.

5) Legal/Policy Restrictions – Some countries ban or restrict VPN usage, which can limit accessibility.
