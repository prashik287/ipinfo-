# System IP Information

This repository provides information about the current system's public IP address, private IP address, and the IP address of the router it's connected to.

## Public IP Address

The public IP address is the IP address assigned to the system by the Internet Service Provider (ISP). It can be used to identify the system on the internet.

To retrieve the public IP address programmatically, you can use services like [ifconfig.io](https://ifconfig.io) or [ipify](https://www.ipify.org).

## Private IP Address

The private IP address is the IP address assigned to the system within a local network. It is used for communication within the network and is not accessible from the internet.

To find the private IP address on Unix/Linux systems, you can use the `ifconfig` command, and on Windows, you can use the `ipconfig` command.

## Router IP Address

The router IP address is the IP address of the router or gateway device that connects the system to the local network and, ultimately, to the internet.

To find the router IP address, you can typically check the default gateway using the `ipconfig` command on Windows or the `route -n` command on Unix/Linux systems.

### Example Usage

```bash
# Retrieve public IP address
curl ifconfig.io

# Retrieve private IP address (Linux)
ifconfig

# Retrieve private IP address (Windows)
ipconfig

# Retrieve router IP address (Linux)
route -n

# Retrieve router IP address (Windows)
ipconfig /all
