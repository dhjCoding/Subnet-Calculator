# Subnet-Calculator# IPv4 Subnet Calculator (Python)

A powerful and accurate IPv4 subnet calculator implemented in Python. This tool helps network engineers, administrators, and developers quickly derive essential networking details from an IP address and its CIDR prefix. It leverages Python's standard `ipaddress` module for reliable and robust calculations.

## 🌟 Features

* **Comprehensive Details:** Calculates network address, broadcast address, total IP addresses in the subnet, and the range of usable host IP addresses.
* **CIDR Support:** Accepts IP addresses with CIDR notation (e.g., `192.168.1.0/24`).
* **Robust Validation:** Utilizes Python's built-in `ipaddress` module for strict validation of IP addresses and CIDR prefixes.
* **Error Handling:** Provides informative error messages for invalid inputs (e.g., malformed IP, invalid CIDR, incorrect data types).
* **Edge Case Aware:** Correctly handles `/31` (point-to-point) and `/32` (single host) networks.
* **Simple API:** A single, intuitive function `calculate_subnet_details` for all calculations.

## 🚀 Installation

No special installation is required beyond a standard Python 3 environment. The `ipaddress` module is part of Python's standard library.

Simply download the `subnet_calculator.py` file and place it in your project directory.

## 🛠️ Usage

### 1. Import the function

```python
from subnet_calculator import calculate_subnet_details
