# 📉 Rockwell PLC Downtime Logger using Python

This project lets you monitor a `Machine_stopped` tag from a Rockwell CompactLogix or ControlLogix PLC and log each downtime event to a CSV file — using Python and the `pylogix` library.

✅ No SCADA required  
✅ CSV-based logging  
✅ Works on Python 3.13

---

## 🚀 Features
- Connects to a Rockwell PLC (CompactLogix/ControlLogix)
- Monitors a BOOL tag (`Machine_stopped`)
- Logs stop events with timestamp, tag name, and status
- Runs on any Python 3.13 environment (PyCharm, terminal, etc.)

---

## 📁 File List

| File             | Description                                |
|------------------|--------------------------------------------|
| `monitor_log.py` | Main script to monitor and log PLC tag     |
| `sample_log.csv` | Sample output of the logging format        |
| `README.md`      | This file                                  |
| `LICENSE`        | Open source MIT license                    |

---

## 🛠️ Requirements

- Python 3.13
- `pylogix` (`pip install pylogix`)
- Rockwell PLC on the same network
- BOOL tag named `Machine_stopped`

---

## 🔧 Setup

1. Install dependencies:
```bash
pip install pylogix
