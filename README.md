# Packet_Sentinel

This is a Simple Network Packet analyzer

# 🌐 Network Traffic Analyzer (Flask + Chart.js)

A lightweight web application that visualizes network traffic by analyzing `.csv` files exported from Wireshark. Built using **Python Flask**, **Chart.js**, and hosted on **Replit**, this tool lets users upload their own traffic data and view **live charts** of top IPs and protocols.

---

## 📌 Features

- 📁 **Upload Wireshark `.csv` files**
- 📊 **Visualize top 5 IP sources and protocols**
- ⚡ **Live bar charts using Chart.js**
- 🎨 Cyber-themed dark UI with neon highlights
- ☁️ Hosted securely on [Replit](https://replit.com)

---

## 🧠 How It Works

1. Capture network traffic using **Wireshark** (Windows or Kali Linux)
2. Export the capture as a `.csv` file:
   - `File > Export Packet Dissections > As CSV`
3. Upload the CSV into the app
4. Flask processes it, extracts the top sources and protocols
5. The frontend displays interactive charts using **Chart.js**

---

## 🖥️ Technologies Used

| Layer       | Tech                   |
| ----------- | ---------------------- |
| Backend     | Python + Flask         |
| Frontend    | HTML + Chart.js + CSS  |
| Analysis    | Pandas (CSV parsing)   |
| Hosting     | Replit (Flask runtime) |
| Packet Data | Wireshark (external)   |

---

## 🔐 Safe & Lightweight

- No live sniffing — only `.csv` file uploads
- No data stored permanently (in-memory processing)
- Max upload size: 2MB

---

## 🚀 How to Use

### ✅ Prerequisites

- Have **Wireshark** installed on your computer

### 🛠️ Steps

1. Capture packets using Wireshark
2. Export as `.csv`
3. Visit the hosted app on Replit
4. Upload your `.csv`
5. View live analytics!

---

## 📁 Example CSV Format

```csv
No.,Time,Source,Destination,Protocol,Length,Info
1,0.000000,192.168.0.2,192.168.0.1,TCP,60,Info...
2,0.001234,192.168.0.3,192.168.0.1,UDP,70,Info...
3,0.002345,192.168.0.2,192.168.0.1,ICMP,80,Info...
```
