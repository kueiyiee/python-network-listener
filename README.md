# 🔒 CodeAlpha Advanced Network Sniffer

A **real-time network packet sniffer and intrusion detection system (IDS)** built with Python.  
This project demonstrates **cybersecurity monitoring, deep packet analysis, and anomaly detection** using scalable and modular architecture.

---

## 🚀 Key Features

### 🔍 Packet Analysis
- Real-time packet capture using **Scapy**
- Protocol support: TCP, UDP, ICMP
- Deep inspection:
  - IP addresses
  - Ports
  - TTL
  - TCP flags
  - Packet size

### 🛡️ Intrusion Detection System (IDS)
- Port scan detection
- SYN flood detection
- Suspicious traffic monitoring
- Packet rate anomaly detection
- IP behavior tracking

### 📊 Real-Time Dashboard
- Live traffic visualization
- Top active IPs and connections
- Alert monitoring panel
- Interactive charts

### 📁 Data Management
- Structured logging system
- JSON and CSV export
- SQLite database support (optional)
- PCAP export for Wireshark

### ⚡ Performance
- Multi-threaded packet processing
- Queue-based architecture
- Optimized for high traffic

---

## 🧱 Project Architecture

```

CodeAlpha_AdvancedNetworkSniffer/
├── src/
│   ├── core/
│   ├── analysis/
│   ├── security/
│   ├── output/
│   ├── interface/
│   └── main.py
├── dashboard/
│   ├── app.py
│   ├── templates/
│   └── static/
├── tests/
├── output/
├── requirements.txt
└── README.md

````

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/CodeAlpha_AdvancedNetworkSniffer.git
cd CodeAlpha_AdvancedNetworkSniffer

python -m venv venv
source venv/bin/activate  # Linux/Mac
# venv\Scripts\activate   # Windows

pip install -r requirements.txt
````

---

## ▶️ Usage

### Run Sniffer

```bash
sudo python src/main.py --protocol tcp --count 50 --verbose
```

### Run Dashboard

```bash
python dashboard/app.py
```

Open browser:

```
http://127.0.0.1:5000
```

---

## 📊 Dashboard Features

* Real-time packet visualization
* Alerts monitoring
* Traffic statistics
* Active connections

---

## 🧪 Testing

```bash
pytest tests/ -v
```

---

## 🔐 Security Notes

* Requires root/admin privileges
* Use only on authorized networks
* Logs may contain sensitive metadata
* Designed for **educational and ethical use only**

---

## 🔮 Future Enhancements

* Machine learning anomaly detection
* GeoIP tracking
* Threat intelligence integration
* Multi-node distributed sniffing
* Advanced AI-based IDS

---

## 👨‍💻 Author

**Kuei Poch Kuei**
Computer Science Student
Cybersecurity & Network Engineering Enthusiast

---

## 📜 License

This project is developed for educational purposes under the CodeAlpha Cybersecurity Internship.
