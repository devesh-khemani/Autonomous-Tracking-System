# Electro-Optical Tracking System — Design Logbook

**Status: 🚧 In Progress**

This logbook documents the design, simulation, and build process for a 4-channel
electro-optical target tracking system, developed independently between June and
September 2024.

## Currently documented in this logbook:
- Analog front-end design and LTspice simulation (transimpedance amplifier +
  cascaded Sallen-Key bandpass filtering, 38 kHz center frequency)
- LM393 Schmitt trigger design for target discrimination
- Mixed-signal PCB layout in KiCad 7 and fabrication via JLCPCB
- Embedded firmware development in C++ on STM32F4 (DMA-driven ADC sampling,
  hardware timer interrupts, real-time control loop)

## Still to be added:
- Dual-axis PID control loop tuning and IMU feed-forward integration
- Software-in-the-loop simulation results and regression test suite
- 2-axis pan-tilt gimbal mechanical design (Fusion 360) and integration
- Final closed-loop validation results and performance data

## Tools & Technologies
LTspice · KiCad 7 · C++ · STM32F4 · Fusion 360

---
*This repository is actively being updated as the write-up is completed. Check back
for the full build log and final results.*
