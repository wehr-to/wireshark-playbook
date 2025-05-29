# 📡 Wireshark Playbook

This repository contains hands-on labs and investigative writeups designed to deepen my understanding of protocol behavior, traffic patterns, and forensic network analysis.

Each lab includes:
- A structured analysis (`lab.md`)
- Practical Wireshark display filters (`filters.txt`)

All traffic scenarios are **hypothetical** and meant to simulate real-world conditions without relying on live captures or sensitive data. This repo focuses on repeatable, manual analysis exercises — no screenshots, no videos, no fluff.

## 🧪 Lab Topics Covered

- TCP 3-way handshakes and sequence flow
- HTTP and DNS request/response behavior
- Normal vs suspicious traffic patterns
- Protocol decoding under load or error
- Detection of scanning, tunneling, and C2 signals
- Effective use of Wireshark filters for triage and hunting

## 📁 Repository Structure

| Folder         | Description                                                    |
|----------------|----------------------------------------------------------------|
| `labs/`         | Core labs — each folder contains a structured writeup and filters |
| `filters/`      | Curated display filters organized by protocol and use case    |
| `methodology/`  | Checklists, dissection strategies, and traffic exploration prompts |
| `templates/`    | Markdown templates for building new labs consistently         |

## 🧠 Lab Philosophy

This repo reflects a few core beliefs:

- **You only learn Wireshark by doing.**
- Packet analysis is a skill, not just a UI.
- Every protocol has a story to tell.
- The best insights come from dissecting the wire, not watching tutorials.

All labs simulate packet activity and behavior based on known RFCs, forensic patterns, and protocol documentation.

## 🧰 How to Use This Repo

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/wireshark-playbook.git
   cd wireshark-playbook
