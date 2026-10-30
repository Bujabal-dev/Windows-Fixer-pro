# Windows-Fixer-pro
> **A comprehensive, single-file hardware stress-test and benchmark suite.**

![Version](https://img.shields.io/badge/version-2.1.0-brightgreen)
![Python](https://img.shields.io/badge/python-3.9%2B-blue)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey)
![License](https://img.shields.io/badge/license-MIT-yellow)

A powerful, open-source tool built with Python and PyQt6. It pushes PC hardware to its limits, measures performance, monitors temperatures, and generates detailed HTML/JSON reports to help you diagnose thermal throttling, check used hardware, or benchmark upgrades.

---

## ✨ Features

### 🧪 Comprehensive Testing
- **CPU Stress**: Multi-threaded burn-in using GEMM, FFT, and integer workloads.
- **RAM Stress**: Sequential fill/verify patterns, bandwidth (GB/s), and latency (ns) measurement.
- **GPU Stress**: Interactive 3D window + heavy offscreen fragment shader.
- **Storage**: Sequential & Random Read/Write, latency (p99), and full SMART health diagnostics.
- **Full System**: Runs all tests in sequence and generates a unified report.

### 📊 Real-Time Telemetry
- Per-core CPU usage and frequency.
- CPU/GPU temperatures and power draw.
- VRAM usage tracking.
- 4 dynamic live charts (CPU / Temp / RAM / Freq).
- Automated **Health Scoring** with smart thermal alerts.

### 🖥️ Universal Hardware Support
- **Discrete GPUs**: Full support via NVML (temps, power, VRAM, utilization).
- **Integrated GPUs (iGPU)**: Read via native OS WMI (VRAM, utilization, temps).
- **Hybrid Systems**: Automatically detects and displays **all** active GPUs simultaneously.
- **No external CLI tools required** (works entirely on native Python libraries).

### 📄 Professional Reports
- **HTML**: Sleek dark-mode report generated and opened automatically in your browser.
- **JSON & CSV**: For automation, data analysis, or live logging.
- **History**: Saves past runs locally for easy comparison.

### 🎨 Modern UI
- Dark and Light mode.
- Save and load custom Presets.
- Specific storage drive selector.
- Instant STOP button.
- Responsive frameless window with edge-resizing.


Note: All rights and publishing belong to me. I permit anyone to use this tool for personal use only. Anyone wishing to develop and distribute it must contact me and obtain my permission.
