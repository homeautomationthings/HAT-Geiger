# Changelog

All notable changes to the HAT Geiger Counter firmware will be documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).
Firmware versioning follows [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [1.0.0] - 2026-03-04

### Added
- Initial release
- CPM and µSv/hr radiation sensing using J321 Geiger tube
- Home Assistant integration via ESPHome native API
- Optional radmon.org upload every 65 seconds
- Radmon username and password configurable from Home Assistant
- Wi-Fi provisioning via BLE (ESPHome app) and USB-C (improv_serial)
- ESPHome dashboard adoption support
- Fallback Wi-Fi hotspot and captive portal
- Safe mode boot button for remote OTA recovery
- SNTP time fallback when Home Assistant is unavailable
- WiFi signal strength (dBm and %) diagnostic sensors
- Uptime, IP address, SSID and firmware version diagnostic sensors
