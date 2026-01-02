# Phase 1 Network Topology

Internet
  |
Virgin Media Hub 5 (Router + Wi-Fi)
  |-- Laptop 1 (Wi-Fi)
  |-- Laptop 2 (Wi-Fi)
  |
  |-- Linksys LGS3xx (Managed Switch)
        |-- Desktop PC (Ethernet)
        |-- Printer (Ethernet)

Security Notes:
- Wi-Fi secured with WPA2/WPA3
- Router hardened (no WPS, no UPnP)
- Switch ports locked to single MAC
- Unused switch ports disabled
