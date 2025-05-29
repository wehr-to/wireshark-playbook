# 🧩 Custom Wireshark Dissectors

This folder contains exploratory Lua-based Wireshark dissectors and supporting documentation. These scripts are used to simulate protocol decoding workflows in hypothetical lab environments.

## ✍️ Files Included

- `myproto.lua`: A basic Lua dissector for a toy protocol over TCP/12345
- `guide-writing-lua-dissectors.md`: Step-by-step how to write and test your own Lua dissectors
- `test-scenarios.md`: Hypothetical packet behaviors for protocol testing (e.g. malformed headers, staged payloads)

## 📂 Usage

1. Place `.lua` scripts in your Wireshark plugin path:
   - **Linux/macOS**: `~/.config/wireshark/plugins/`
   - **Windows**: `%APPDATA%\Wireshark\plugins\`

2. Restart Wireshark.

3. Generate or replay traffic to the specified port (e.g., TCP 12345).

> 💡 Dissectors here are for education and lab simulation only — they are not tied to any real production traffic or proprietary protocols.

## 📌 Why This Exists

Creating your own dissectors forces you to:
- Understand how protocols are structured at the byte level
- Think critically about field alignment, interpretation, and control flow
- Apply forensic techniques when source protocols aren’t well-documented

This folder reflects my effort to learn protocol dissection *from the ground up*.



