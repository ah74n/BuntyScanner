# BuntyScanner
BuntyScanner is an Automated Port Scanner with VPN Rotation A web-based port scanning tool built with Python and Flask that combines automated VPN rotation with TCP port probing. Designed to simulate anonymized network reconnaissance by rotating egress IPs between scan batches.

What It Does

Scans a target IP or domain across a configurable port range Rotates VPN profiles between scan batches to vary the source IP Verifies the egress IP has actually changed before each batch (leak detection) Displays live results in a browser-based dashboard with real-time terminal output Saves discovered open ports to a local JSON file

Tech Stack

Backend : Python, Flask Tunneling : OpenVPN (subprocess-controlled) Frontend : HTML, Tailwind CSS, vanilla JS Networking : Python socket module for TCP connect scanning

⚠️Currently i am facing issue with the free vpn it fails again and again i am working on it, will be live soon⚠️
