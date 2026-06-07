 Network Task 02

 1. Objective

The purpose of this task is to understand common network devices, IP addressing concepts, and how data travels within a network. This task also helps in learning how DNS, routers, and network communication work in real-world environments.

---

2. Network Devices Research

 Router

**Purpose:** Connects different networks and provides internet access.

**How it works:** Receives data packets and forwards them to the correct destination.

**Real-world usage:** Home WiFi routers such as JioFiber routers.

Switch

**Purpose:** Connects devices within a Local Area Network (LAN).

**How it works:** Uses MAC addresses to send data only to the intended device.

**Real-world usage:** Office and college networks.

 Hub

**Purpose:** Connects multiple devices in a network.

**How it works:** Broadcasts incoming data to all connected devices.

**Real-world usage:** Older or very small networks.

 Access Point

**Purpose:** Provides wireless connectivity to devices.

**How it works:** Extends a wired network into a wireless network.

**Real-world usage:** WiFi networks in schools, colleges, and offices.

 Firewall

**Purpose:** Protects the network from unauthorized access.

**How it works:** Filters incoming and outgoing network traffic.

**Real-world usage:** Windows Firewall and enterprise security systems.

 Modem

**Purpose:** Connects a home or office network to an Internet Service Provider (ISP).

**How it works:** Converts ISP signals into internet connectivity.

**Real-world usage:** JioFiber modem.

---

3. IP Address Classification

| IP Address    | Type    | Reason                                       |
| ------------- | ------- | -------------------------------------------- |
| 192.168.1.10  | Private | Belongs to 192.168.x.x private range         |
| 10.0.0.5      | Private | Belongs to 10.x.x.x private range            |
| 172.16.5.20   | Private | Belongs to 172.16.0.0 – 172.31.255.255 range |
| 8.8.8.8       | Public  | Google's public DNS server                   |
| 1.1.1.1       | Public  | Cloudflare public DNS server                 |
| 192.168.100.1 | Private | Belongs to 192.168.x.x private range         |

---

 4. Understanding My Network

 Network Information

* Hostname: L*****-*******
* IPv4 Address: 192.168.31.xxx
* Default Gateway: 192.168.31.x
* DNS Server: 192.168.31.x

 Which IP range does your device belong to?

My device belongs to the 192.168.x.x private IP address range.

 Is it Public or Private?

It is a Private IP address because it is used within a local network and is not directly accessible from the internet.

 What role does your router play in your network?

The router connects my local network to the internet and forwards data packets between my device and external servers.

 What would happen if the DNS server stopped working?

If DNS stopped working, websites could not be accessed using domain names such as google.com because domain names would not be translated into IP addresses.

---

 5. Network Communication Flow

 Diagram

Your Device
↓
JioFiber Router
↓
DNS Server
↓
Google Server
↓
Response Back to Device

Explanation

Step 1

The user enters [www.google.com](http://www.google.com) in a web browser.

Step 2

The request is sent from the device to the router.

 Step 3

The router contacts a DNS server to find the IP address of google.com.

 Step 4

The DNS server returns the IP address of Google's server.

 Step 5

The request is sent to Google's server using the IP address.

 Step 6

Google processes the request and sends the webpage data back to the user's device.

---

 6. Practical Command Exercise

 ipconfig /all

Hostname: L*****-*******

IPv4 Address: 192.168.31.xxx

Default Gateway: 192.168.31.x

DNS Server: 192.168.31.x

---

nslookup google.com

Server: jiofiber.local.html

Server Address: 192.168.31.x

Google IPv4 Address:
***

Google IPv6 Address:
2404:6800:4009:805::***

 What IP address did DNS return for Google?

DNS returned the IPv4 address 142.250.77.142 and the IPv6 address 2404:6800:4009:805::200e.


ping google.com

Result: Successful

Packets Sent: 4

Packets Received: 4

Packet Loss: 0%

Was the ping successful?

Yes, the ping was successful because all packets were received without any packet loss.

 Why is DNS important before communication begins?

DNS converts domain names such as google.com into IP addresses that computers use to communicate over the internet.

---

 7. Conclusion

This task improved my understanding of network devices, IP addressing, DNS resolution, and network communication. I learned how routers, DNS servers, and internet services work together to establish communication between devices and websites.
