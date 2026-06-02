# System Diagnostics for LAN

A robust, lightweight network and system monitoring tool designed to analyze, diagnose, and report the health and performance of machines across a Local Area Network (LAN). This project helps network administrators and developers track system metrics, monitor active hosts, and troubleshoot connectivity bottlenecks seamlessly.

---

## 🚀 Features

*   **Real-Time Node Discovery:** Automatically scans, pings, and identifies active devices and open ports across local network subnets.
*   **System Metrics Aggregation:** Monitors critical host performance indicators including CPU utilization, memory allocation, and disk usage.
*   **Network Diagnostic Utilities:** Built-in utilities for latency testing (Ping), path tracing (Traceroute), and network stability checks.
*   **Lightweight Footprint:** Optimized to run quietly in the background without hogging local network bandwidth or system resources.
*   **Structured Reporting:** Generates clear console outputs or log summaries detailing the overall status of the LAN ecosystem.

---

## 🛠️ Tech Stack

*   **Core Logic:** Python / Node.js (Cross-platform compatibility)
*   **Networking Protocols:** ICMP (Ping), TCP/UDP scanning, Raw Sockets
*   **Data Formatting:** JSON / Markdown logs for easy integration

---

## 📋 Prerequisites

Before running this project, ensure you have the following ready:
*   **Runtime environment:** Python 3.8+ OR Node.js v18+ installed on your machine.
*   **Privileges:** Administrative/Root privileges are highly recommended. (Certain raw socket operations, like deep ICMP pinging, require elevated permissions on Windows, macOS, and Linux).

---

## 🔧 Installation & Setup

### 1. Clone the Repository
```bash
git clone [https://github.com/harsh20048/System-Diagnostics-for-LAN.git](https://github.com/harsh20048/System-Diagnostics-for-LAN.git)
cd System-Diagnostics-for-LAN
