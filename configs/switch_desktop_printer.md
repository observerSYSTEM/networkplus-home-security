# Linksys LGS3xx — Switch Hardening

## Ports
- Desktop-PC: enabled, MAC limit = 1
- Printer: enabled, MAC limit = 1
- Unused ports: disabled
- Uplink-to-Hub5: enabled

## Security
- Port security enabled (shutdown on violation)
- Management access restricted to wired desktop
- Configuration saved to startup

## Result
Physical access risks mitigated; device swapping prevented.
# Managed Switch Configuration – Desktop & Printer

## VLAN Design
- VLAN 10: Desktop (trusted)
- VLAN 20: Printer (restricted)
- VLAN 99: Switch management

## Port Configuration
- Desktop port: Access VLAN 10
- Printer port: Access VLAN 20
- Unused ports: Disabled

## Port Security
- MAC address limit: 1
- Violation mode: Shutdown

## Network+ Concepts
- VLAN segmentation
- Access ports
- Port security
- Layer 2 isolation
