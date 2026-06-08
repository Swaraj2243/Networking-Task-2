# Networking Task 02

## Student Information

**Name:** Swaraj Jadhav

---

# Part A: Network Devices Research

## 1. Router

### Purpose
A router connects different networks and allows devices to access the internet.

### How It Works
It receives data packets from devices and forwards them to the correct destination using IP addresses.

### Real-World Usage
Used in homes, offices, and schools to connect multiple devices to the internet.

---

## 2. Switch

### Purpose
A switch connects multiple devices within the same network.

### How It Works
It uses MAC addresses to send data directly to the intended device.

### Real-World Usage
Used in offices, computer labs, and data centers.

---

## 3. Hub

### Purpose
A hub connects multiple devices in a network.

### How It Works
It broadcasts incoming data to all connected devices.

### Real-World Usage
Older networks used hubs before switches became common.

---

## 4. Access Point

### Purpose
Provides wireless connectivity to devices.

### How It Works
It converts wired network signals into Wi-Fi signals.

### Real-World Usage
Used in homes, schools, airports, and cafes.

---

## 5. Firewall

### Purpose
Protects a network from unauthorized access.

### How It Works
It monitors and filters incoming and outgoing traffic based on security rules.

### Real-World Usage
Used in personal computers, businesses, and enterprise networks.

---

## 6. Modem

### Purpose
Connects a network to an Internet Service Provider (ISP).

### How It Works
It converts digital signals into signals suitable for transmission over internet lines.

### Real-World Usage
Used in homes and offices to access the internet.

---

# Part B: IP Address Classification

| IP Address | Category | Explanation |
|------------|----------|-------------|
| 192.168.1.10 | Private | Falls within 192.168.0.0 – 192.168.255.255 private range |
| 10.0.0.5 | Private | Falls within 10.0.0.0 – 10.255.255.255 private range |
| 172.16.5.20 | Private | Falls within 172.16.0.0 – 172.31.255.255 private range |
| 8.8.8.8 | Public | Public Google DNS server accessible on the internet |
| 1.1.1.1 | Public | Public Cloudflare DNS server accessible on the internet |
| 192.168.100.1 | Private | Falls within the 192.168.x.x private range |

---

# Part C: Understanding Your Network

## IPv4 Address
Example: 192.168.31.21

## Default Gateway
Example: 192.168.31.1

## DNS Server
Example: 192.168.31.1

### Which IP range does your device belong to?
My device belongs to the 192.168.x.x range.

### Is it Public or Private?
It is a Private IP address.

### What role does your router play in your network?
The router connects my local devices to the internet and directs data between networks.

### What would happen if the DNS server stopped working?
Websites would not open using domain names because the DNS server translates domain names into IP addresses. Users would need to enter IP addresses manually.

### Screenshots
Add screenshots of:
- ipconfig /all
- Network settings
- DNS information

---

# Part D: Network Communication Flow

## Diagram

```text
Your Device
     ↓
   Router
     ↓
 DNS Server
     ↓
Google Server
     ↓
Response Back
     ↓
Your Device
```

## Explanation

### Step 1: User Request
The user enters www.google.com in a web browser.

### Step 2: Router Forwarding
The router forwards the request toward the DNS server.

### Step 3: DNS Resolution
The DNS server converts www.google.com into an IP address.

### Step 4: Contact Google Server
The request is sent to Google's server using the resolved IP address.

### Step 5: Server Response
Google's server processes the request and sends data back.

### Step 6: Display Website
The browser receives the response and displays the webpage.

---

# Part E: Practical Command Exercise

## Windows Commands

### ipconfig /all
Displays detailed network configuration information.

### nslookup google.com
Returns the IP address associated with Google.

### ping google.com
Tests connectivity between the device and Google's server.

---

## Answers

### What IP address did DNS return for Google?

Example:

```text
142.250.183.78
```

(Your result may vary.)

### Was the ping successful?

Yes, the ping was successful if replies were received from Google.

### Why is DNS important before communication begins?

DNS translates human-readable domain names into IP addresses, allowing devices to locate and communicate with servers on the internet.

---


# Conclusion

This task helped me understand networking devices, IP address classification, DNS functionality, and how communication occurs between a client device and a web server. It also provided practical experience with networking commands and network troubleshooting tools.
