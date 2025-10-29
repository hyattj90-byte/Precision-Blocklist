# Precision-Blocklist
 Cross-OS, router-isolated DNS blocklist idea to be tested on commercially available flagship devices. Apple, Android and Windows- no emulators. No bleed-over. Just reproducible telemetry.

This blocklist would be curated through real-world testing on flagship consumer hardware:
Lab Architecture
Apple
• iPhone 17 Pro Max (1TB)
• iPad Pro M4 (1TB)
• MacBook Pro M4 (2TB)
• iMac (M3 or M4, depending on availability) 4TB SSD
Android
• Google Pixel 9 Pro XL (1TB
• Samsung Galaxy S25 Ultra (1TB)
Windows
• Surface Laptop Studio 3 (2TB SSD)
• Custom-built desktop (4TB SSD, 64GB RAM, isolated NICs for DNS capture)
Network Isolation Strategy
Each device is assigned a dedicated SSID and VLAN via router-level segmentation to ensure:
• Clean telemetry attribution
• No cross-device bleed-over
• No enterprise contamination
• No synthetic traffic injection
This architecture guarantees that every DNS query is tied to a specific device, OS, and app context - enabling forensic-grade analysis of telemetry behavior across platforms.
