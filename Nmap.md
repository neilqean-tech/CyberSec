# 🔎 Nmap (Network Mapper)

## 📥 Installation

Download Nmap from the official website:
https://nmap.org/download.html

---

##  More Command

Refer to this website:
https://www.stationx.net/nmap-cheat-sheet/

---

## 🚀 Basic Usage

### 1. Check if Nmap is installed

```bash
nmap --version
```

---

### 2. Get your IP address

```bash
ipconfig
```

---

### 3. Scan your network

```bash
nmap -sn 192.168.1.0/24
```

* Scans all devices connected to your network

---

### 4. Scan a specific IP

```bash
nmap -sS 192.168.1.1
```

* Scans open ports on a target

---

### 5. Detect operating system

```bash
nmap -O 192.168.1.1
```

* Tries to guess the OS of the target

---

### 6. Detect service versions

```bash
nmap -sV 192.168.1.1
```

* Shows versions of services running on open ports

---

### 7. UDP scan

```bash
nmap -sU 192.168.1.1
```

* Scans UDP ports

---

### 8. Run scripts (example)

```bash
nmap --script=http-headers nmap.org
```

* Displays HTTP header information

---

## 🧠 What I Learned

* How to scan my network
* How to find open ports
* How to detect OS and services
* Basic Nmap commands

---

## ⚠️ Important

Only scan networks and systems you own or have permission to test.

---

⭐ More notes coming as I learn deeper.
