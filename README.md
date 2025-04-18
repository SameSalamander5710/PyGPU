[Work in progress]

# PyGPU

**PyGPU** is a lightweight Python module that uses `ctypes` to directly interface with the Windows Performance Data Helper (PDH) API and retrieve real-time GPU utilization data — **no WMI, no PowerShell, no external dependencies, and is GPU-vendor agnostic**.

This is ideal for performance monitoring or dynamic system tuning where speed and efficiency matter. As an example, this is used in [DynamicFPSLimiter v4](https://github.com/SameSalamander5710/DynamicFPSLimiter), a real-time FPS control tool using PyGPU and RTSS.

PyGPU uses:
- Python Standard Library
- `ctypes` for native Windows API access
- `collections`, `re`, `time` — nothing extra needed

## Getting Started

To see how to use `PyGPU` in your own project, take a look at the included [`Example.py`](./Example.py) script.

The underlying code may be modified to get other counters as well. 
