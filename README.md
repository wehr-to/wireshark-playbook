# 📡 Wireshark Playbook

This repository contains hands-on labs, packet captures, and investigative writeups designed to deepen my understanding of protocol behavior, traffic patterns, and forensic network analysis.

Each lab includes:
- A structured analysis (`lab.md`)
- Useful Wireshark display filters

The goal is to build real fluency in packet inspection without relying on screenshots, videos, or surface-level explanations — this is **manual, grounded, and repeatable network analysis**.

## 🧪 Lab Topics Covered

- TCP 3-way handshakes and sequence flow
- HTTP and DNS request/response behavior
- Normal vs suspicious traffic patterns
- Protocol decoding under load or error
- Detection of scanning, tunneling, and C2 signals
- Effective use of Wireshark filters for triage and hunting

## 📁 Repository Structure

| Folder         | Description                                                   |
|----------------|---------------------------------------------------------------|
| `labs/`         | Core labs — each folder contains a `.pcapng`, lab writeup, and filters |
| `filters/`      | Curated filter expressions by protocol, use case, or behavior |
| `methodology/`  | Repeatable analysis checklists, dissection flows, traffic ideas |
| `templates/`    | Template for documenting new labs in a consistent format       |

## 🧠 Lab Philosophy

This repo reflects a few core beliefs:
- **You only learn Wireshark by doing.**
- Packet analysis is a skill, not a tool.
- Every protocol has something to teach you.
- The best insights come from reading the wire directly.

## 🧰 How to Use This Repo

1. Clone it:
   ```bash
   git clone https://github.com/yourusername/wireshark-playbook.git
   cd wireshark-playbook

