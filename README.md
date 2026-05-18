# DUNEN Dashboard Read-Only Pro

Full clean iOS project for GitHub Actions.

Includes:
- Liquid glass bottom tabs
- Info / Advanced / Diagnostics / Settings
- App icon included
- Aptum 8F startup animation image included
- No ContentView.swift
- No RideSensorManager.swift
- No iPhone GPS speed
- No iPhone tilt sensors
- No tuning/write controls

Read-only features:
- Speed from BLE packet guess
- RPM lower/right inside speedometer
- Odometer
- Voltage
- SOC
- Controller temp
- Motor temp
- Throttle %
- Current / phase current
- Brake sensors
- Kickstand/stand sensor
- Reverse status
- Regen status
- Eco/Sport mode
- Protection / fault screen
- Controller identity screen
- Raw BLE packet logger

Important:
The BLE parser uses placeholder/best-guess byte offsets. It connects to FFE0/FFE1 and logs packets, but exact DUNEN values may need byte mapping from your real raw packets.

Build:
1. Delete old repo files.
2. Upload everything from this ZIP to repo root.
3. Run GitHub Actions: Build iOS IPA.
4. Install the artifact using Sideloadly.
