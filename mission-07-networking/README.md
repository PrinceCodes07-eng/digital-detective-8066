# Mission 7 – How Computers Communicate

## Mission Objective

Understand basic networking concepts, observe network connectivity and DNS information using Terminal, and explain how computers communicate when opening a website.

---

## Task 7.1 – Network Concepts

Computer networks allow devices to communicate, exchange information and share resources.

| Concept | Explanation in My Own Words | Example |
|---|---|---|
| LAN | A network connecting devices within a small geographical area. | Home Wi-Fi or college computer lab |
| MAN | A network connecting devices across a city or large campus. | Network connecting different college campuses in a city |
| WAN | A network covering large geographical areas, such as countries or continents. | The Internet |
| DNS | Converts a website's domain name into its corresponding IP address. | Converting google.com into an IP address |
| Router | Connects different networks and forwards data between them. | Home Wi-Fi router |
| Protocol | A set of rules that devices follow to communicate with each other. | HTTP, HTTPS and TCP |
| Packet Switching | Divides data into smaller packets that travel through a network and are reassembled at the destination. | Sending information over the Internet |

---

## Task 7.2 – Observe Network Information

### 1. Connectivity Test

**Tool used:** Terminal

**Command:**
```bash
ping -c 4 example.com
```

**Observation:**

- The connectivity test was successful.
- All 4 packets received replies.
- The resolved IP address was 172.66.147.243.
- The response time was approximately 20–22 milliseconds.

**What I Learned:**

A connectivity test helps check whether my computer can communicate with another device or server over a network. It also provides information about packet responses and network delay.

### 2. DNS Lookup

**Tool used:** Terminal

**Command:**
```bash
nslookup example.com
```

**Observation:**

- The DNS server used was 8.8.8.8.
- The DNS server responded successfully.
- Two IP addresses were returned:
  - 172.66.147.243
  - 104.20.23.154

**What I Learned:**

A DNS lookup displays the IP address associated with a domain name. DNS helps browsers locate websites by translating human-readable domain names into IP addresses.

### Role of DNS

When we enter a website name in a browser, DNS helps find the corresponding IP address. The browser can then use that address to communicate with the website's server.

**Privacy Note:** Personal network information, such as private IP addresses and Wi-Fi names, has not been included.

---

## Task 7.3 – What Happens When You Open a Website?

The following steps explain how a website opens:

1. **Client Request:** The user enters a website address in a browser. The browser acts as a client and starts the request.

2. **DNS Lookup:** DNS translates the domain name into an IP address so the browser can locate the website's server.

3. **Network Communication:** The request travels through the local network and router towards the destination server.

4. **Server Receives Request:** The website's server receives and processes the client's request.

5. **Server Response:** The server sends the requested website data back using communication protocols such as HTTP or HTTPS.

6. **Browser Displays Website:** The browser processes the received HTML, CSS and JavaScript and displays the webpage to the user.

---

## Tools and Commands Used

| Tool / Command | Purpose |
|---|---|
| `ping -c 4 example.com` | Tests network connectivity by sending four packets. |
| `nslookup example.com` | Finds the IP addresses associated with a domain name. |
| Terminal | Used to execute networking commands and observe network information. |

---

## What I Learned

Through this mission, I learned:

- The differences between LAN, MAN and WAN.
- How DNS converts domain names into IP addresses.
- The role of routers in connecting networks.
- How protocols allow devices to communicate.
- How packet switching transfers data across networks.
- How to check connectivity using ping.
- How to perform DNS lookups using nslookup.
- How a browser communicates with a server to display a website.

## Difficulties Faced

Initially, I needed to understand the output of networking commands. I learned how to interpret the ping response time, packet replies, DNS server address and IP addresses returned by nslookup.

## How I Solved the Difficulty

I reviewed the output of the networking commands and identified the important information.

- In `ping`, I checked packet replies and response time.
- In `nslookup`, I identified the DNS server and returned IP addresses.

This helped me understand how to interpret basic network information.

## Evidence and Files

- `README.md` – Contains the network concepts table, command observations, website communication steps and learning outcomes.

## Conclusion

This mission helped me understand how computers communicate over networks. I also learned how DNS, routers, protocols and client-server communication work together when opening a website.

## Commit Details

- Commit message: `Explain networking concepts and website communication`
- Changes pushed to GitHub: Yes