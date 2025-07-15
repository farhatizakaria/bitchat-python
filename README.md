# 📡 BitChat Python

A **Python implementation** of [BitChat](https://github.com/permissionlesstech/bitchat) — a **decentralized, peer-to-peer, encrypted chat** application over **Bluetooth Low Energy (BLE)**.

This project is a rewrite of the original, aimed at bringing similar functionality into Python for easier development, learning, and extensibility.

---

## 🚀 Features

- 📶 BLE (Bluetooth Low Energy) communication
- 🔐 End-to-end encryption using `cryptography`
- 📦 Lightweight design
- ⚙️ Data compression via `lz4`
- 🌱 Probabilistic message deduplication using `pybloom`
- 🧪 Async I/O with `aioconsole` for better responsiveness

---

## 📦 Install
```bash
git clone https://github.com/farhatizakaria/bitchat-python.git
cd bitchat-python
```

Make sure you have Python 3.11+ installed.

Install all required packages:

```bash
pip install -r requirements.txt
```
```bash
python3 bitchat.py 
```
