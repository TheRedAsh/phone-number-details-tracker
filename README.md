# 📞 Phone Number Details Tracker 📡

A lightweight, zero-dependency Python command-line utility designed for automated OSINT (Open Source Intelligence) and reconnaissance of Pakistani mobile numbers and CNICs. It aggregates multiple public open-source threat intelligence resources to map ownership profiles instantly.

---

## 🔥 Key Features
- **Dual Lookup Engine:** Easily perform queries using either a Mobile Number or CNIC.
- **Deep Target Profiles:** Retrieves Name, CNIC, Address, Province detection, and active Carrier.
- **Auto-Crash Protection:** Features robust response structure handling (`list`/`dict` parsing) to prevent API payload crashes.
- **Automated Google Dorks:** Generates pre-formatted search dorks tailored to Pakistani platforms (OLX, PakWheels, Facebook, etc.) for further manual investigation.
- **Local Reporting:** Option to save full intelligence reports as structured `.json` or clean readable `.txt` files.

---

## 🛠️ Installation & Setup (Kali Linux)

Open your terminal and execute the following instructions to set up the repository:

```bash
# 1. System packages aur Python ko update/install karein
sudo apt update && sudo apt install git python3 python3-pip -y

# 2. Repository ko clone karein
git clone [https://github.com/TheRedAsh/phone-number-details-tracker.git](https://github.com/TheRedAsh/phone-number-details-tracker.git)

# 3. Directory me dakhil hon
cd phone-number-details-tracker
💻 How to Run
Workspace setup karne ke baad tool ko execute karne ki standard command:

Bash
python3 phone_tracker.py
