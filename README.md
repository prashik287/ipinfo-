<h1 align="center">🖥️ IPINFO</h1>

<p align="center">
  <img src="https://img.shields.io/badge/build-alpha-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/github/stars/yourusername/system-ip-information?style=for-the-badge" />
  <img src="https://img.shields.io/github/issues/yourusername/system-ip-information?style=for-the-badge" />
</p>

> 🌐 *This tool provides information about the current system's public IP address, private IP address, and the IP address of the router it's connected to, based on different interfaces.*  

---

## 📡 Overview of the Project

The IPINFO script is designed to help users easily retrieve and display their network-related IP addresses. It provides information about:

- **Public IP Address**: The IP address assigned to the system by the Internet Service Provider (ISP).
- **Private IP Address**: The IP address assigned to the system within a local network.
- **Router IP Address**: The IP address of the router or gateway device connecting the system to the internet.

---

## 🌍 Public IP Address

The public IP address is the IP address assigned to the system by the Internet Service Provider (ISP). It can be used to identify the system on the internet.

To retrieve the public IP address programmatically, you can use services like [ifconfig.io](https://ifconfig.io) or [ipify](https://www.ipify.org).

---

## 🏠 Private IP Address

The private IP address is the IP address assigned to the system within a local network. It is used for communication within the network and is not accessible from the internet.

To find the private IP address:
- On Unix/Linux systems, you can use the `ifconfig` command.
- On Windows, you can use the `ipconfig` command.

---

## 🛠️ Router IP Address

The router IP address is the IP address of the router or gateway device that connects the system to the local network and, ultimately, to the internet.

To find the router IP address:
- On Windows, check the default gateway using the `ipconfig` command.
- On Unix/Linux systems, use the `route -n` command.

---

## 📚 Getting Started

**Initialize in T-minus 3 steps:**

```bash
# Clone the repository
git clone https://github.com/yourusername/system-ip-information.git
cd system-ip-information

# Install dependencies (if any)
# For example, if using Python:
pip install -r requirements.txt

# Run the application
python app.py
