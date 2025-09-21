# SDR# Setup Guide

This document explains how I set up my **RTL-SDR V4 dongle** and received my first FM signals.
Detailed Steps are available as a pdf in the main repo, with images
---

## Hardware
- RTL-SDR Blog V4 dongle  
- Laptop (Windows 10/11)  
- Temporary antenna: 18 AWG copper wire (~75 cm, quarter-wave for FM)  
- Planned: RG-58 coax + SMA connectors for a proper dipole  

---

## Software Setup
1. Downloaded [**SDR# (SDRSharp)**](https://airspy.com/download/)  
2. Installed drivers using Zadig (included in SDR# package).  
3. Opened SDR# and confirmed that the RTL-SDR device was detected.  

---

## First Reception
- Inserted a 75 cm copper wire into the SDR’s SMA connector as a temporary antenna.  
- Tuned to the **FM broadcast band (88–108 MHz)**.  
- Successfully received **92.7 MHz** and **104 MHz** FM stations   
---

## Observations
- Vertical wire orientation gave clear reception.  
- Horizontal orientation gave almost nothing → confirms FM is mainly vertically polarized here.  
- Reception improved near windows or elevated positions.  

---

## Next Steps
- Build a half-wave dipole for FM (~1.5 m total length).  
- Use RG-58 coax + SMA connector for better matching.  
- Add a 1:1 balun to reduce noise.  
- Try **ADS-B (1090 MHz)** with a dedicated antenna.  
- Explore ham radio CW signals (with upconverter for HF).

## References
- [RTL-SDR Blog](https://www.rtl-sdr.com/)  
- [SDRSharp Software](https://airspy.com/download/)  
- [Dipole Antenna Length Calculator](https://www.everythingrf.com/rf-calculators/dipole-antenna-length-calculator)  
