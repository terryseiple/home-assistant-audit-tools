# Entity & Device Audit for Home Assistant

A custom integration designed to audit entities and devices for naming hygiene, orphaned references, and zone-aware orchestration clarity.

## 🔍 Features
- Flags entities without associated devices
- Identifies devices lacking user-defined names
- Supports persistent notifications for audit results
- Modular structure for extending validators (e.g., naming, zone filters)

## 🚀 Installation
1. Clone this repo into your Home Assistant config:
   ```bash
   git clone https://github.com/terryseiple/home-assistant-audit-tools.git
