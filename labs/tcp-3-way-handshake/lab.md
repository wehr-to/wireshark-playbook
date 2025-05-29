# Lab: TCP 3-Way Handshake

## 📄 Lab Objective
Observe and analyze a complete TCP 3-way handshake, including sequence numbers, flags, and options.

## 📂 File
- `capture.pcapng`: Contains SYN → SYN-ACK → ACK between client and server.

## 🔍 Investigation Notes
- SYN from 10.0.0.10 to 10.0.0.20 on port 443
- MSS and window scale options present
- No retransmissions
- Initial sequence numbers noted for both sides

## 🔎 Useful Filters
```wireshark
tcp.flags.syn == 1 && tcp.flags.ack == 0     # SYN
tcp.flags.syn == 1 && tcp.flags.ack == 1     # SYN-ACK
tcp.flags.ack == 1 && tcp.flags.syn == 0     # Final ACK
ip.addr == 10.0.0.10 && tcp.port == 443
