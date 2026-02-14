# 🖧 Network Scanner (Active Host & MAC Address Discovery)

## ⚠ Disclaimer

This tool is developed strictly for **educational purposes and authorized network security testing**.  
Do NOT scan networks without proper permission. Unauthorized scanning may violate laws and policies.

---

## 📌 Overview

This is a basic Python-based Network Scanner.

The script:
- Takes an IP range as input (e.g., 192.168.1.1/24)
- Scans the network for active devices
- Identifies live hosts
- Retrieves their MAC addresses

This tool is useful for:
- Network reconnaissance
- Device discovery
- Internal lab testing
- Understanding ARP-based communication

---


⚠ Note: This script may require administrative/root privileges to run properly.

---

## ⚙ How It Works

1. User enters an IP range (CIDR format recommended).
2. Script sends ARP requests to the specified range.
3. Devices that respond are considered active.
4. The script collects:
   - IP Address
   - MAC Address
5. Results are displayed in a structured format.

Example Output:

```text
192.168.1.1    00:1A:2B:3C:4D:5E
192.168.1.5    98:76:54:32:10:AA
```


## 🎯 Learning Outcomes

By building this project, you understand:

- ARP (Address Resolution Protocol)
- Packet crafting and broadcasting
- Host discovery techniques
- MAC address identification
- Basic internal network reconnaissance
- How attackers map networks before exploitation

---

## ⚡ Limitations

- Works best in local networks
- Requires root/admin privileges
- Does not scan ports
- No OS detection
- Sequential scanning (if no threading implemented)

---

## 🛡 Defensive Awareness

To protect against unauthorized scanning:

- Monitor unusual ARP traffic
- Use network intrusion detection systems (NIDS)
- Implement VLAN segmentation
- Enable port security on switches
- Monitor unknown MAC addresses

---

## 👨‍💻 Author

Himanshu  
Cybersecurity Enthusiast | Python Developer | Ethical Hacking Learner




