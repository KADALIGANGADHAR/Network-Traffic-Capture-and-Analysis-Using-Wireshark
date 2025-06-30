# 📡 Network-Traffic-Capture-and-Analysis-Using-Wireshark

## 🧾 Objective

To capture live network traffic using Wireshark, filter packets by protocol, identify different traffic types, and gain hands-on experience in protocol analysis.

---

## 🛠 Tools Used

- OS: **Kali Linux**
- Application: **Wireshark** (pre-installed in Kali)
- Browser: **Firefox**


---

## 🔍 Steps Performed

### ✅ Step 1: Installed Wireshark

- Downloaded from official site and installed with Npcap.

### ✅ Step 2: Captured Live Traffic

- Captured traffic from the active network interface for 60 seconds.
- Generated traffic by:
  - Visiting `example.com`
  - Running `ping google.com`
![kali-linux-2024 4-vmware-amd64-2025-06-30-16-04-35](https://github.com/user-attachments/assets/03df5425-e00b-4e3b-92d1-c0728206263e)
![kali-linux-2024 4-vmware-amd64-2025-06-30-16-13-06](https://github.com/user-attachments/assets/ed0c870e-32e4-48e3-ae8b-2b767d1ab9a4)
![kali-linux-2024 4-vmware-amd64-2025-06-30-16-14-03](https://github.com/user-attachments/assets/b7087262-21af-41d9-a7c9-898b7a3e5103)
![kali-linux-2024 4-vmware-amd64-2025-06-30-16-14-18](https://github.com/user-attachments/assets/4959bc08-ca3e-4e67-bd4b-1b4182e85eb6)
![kali-linux-2024 4-vmware-amd64-2025-06-30-18-29-37](https://github.com/user-attachments/assets/ca934784-9da6-4912-92ad-8207472a12b0)


### ✅ Step 3: Filtered Packets

- **HTTP**: `http` filter showed HTTP GET requests.
- **DNS**: `dns` filter showed DNS request/response packets.
- **TCP**: `tcp` filter showed TCP handshake and communication.
![kali-linux-2024 4-vmware-amd64-2025-06-30-18-31-13](https://github.com/user-attachments/assets/b57d6a92-b876-4c5c-bc49-68604bf00d92)
![kali-linux-2024 4-vmware-amd64-2025-06-30-18-31-18](https://github.com/user-attachments/assets/4f53f05a-a636-4dff-9ef3-bcb5b94b190d)
![kali-linux-2024 4-vmware-amd64-2025-06-30-18-31-28](https://github.com/user-attachments/assets/b540ff73-3370-4c9e-9036-be45e96ee4bb)
![kali-linux-2024 4-vmware-amd64-2025-06-30-18-31-32](https://github.com/user-attachments/assets/3b9766ad-5e30-4b32-88d0-6cedf2aad66a)
![kali-linux-2024 4-vmware-amd64-2025-06-30-18-31-44](https://github.com/user-attachments/assets/59ce0598-9ff9-4689-8bb1-4edd08b77583)
![kali-linux-2024 4-vmware-amd64-2025-06-30-18-31-50](https://github.com/user-attachments/assets/3345a9b4-f4c9-47b0-9bf6-94f719090f0d)

### ✅ Step 4: Identified Protocols

- Observed the following:
  - HTTP
  - DNS (port 53)
  - TCP (port 443, 80)

- Used Statistics → Protocol Hierarchy to visualize data.

### ✅ Step 5: Saved Capture

---

## 🧠 Summary

> Wireshark is a powerful tool that captures and analyzes packets on a network. It helped identify DNS queries, TCP handshakes, and HTTP traffic, giving insight into how devices communicate and resolve domains.


---

## ✅ Outcome

- Gained experience in live packet capture
- Learned to filter and analyze common network protocols
- Understood how tools like Wireshark are used for troubleshooting and security analysis
