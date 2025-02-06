# Network-Traffic-Visualizer

A lightweight Python tool to **capture and visualize** network traffic in real time. Built using [Scapy](https://scapy.net/) and `matplotlib` (or any plotting library you prefer).

## Overview
It sniffs packets from your network interface, parses protocol details (TCP, UDP, ICMP, etc.), and shows **live stats** (like packet count, bandwidth usage, or protocol distribution).

### Features
- Real-time packet capture with Scapy.
- Basic filtering (e.g., show only TCP or traffic to a certain IP).
- Live visualization (using Matplotlib, Plotly, or terminal dashboards).

## Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/youruser/PacketScope.git
   cd PacketScope
