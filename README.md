# Digital Oscilloscope

A digital oscilloscope program for the TI EK-TM4C1294XL Board with TI BOOSTXL-EDUMKII Booster Pack.

Features:
- Color display of input waveform and UI
- Real time operating system
- 120 MHz clock speed
- Adjustable graph axes
- Frequency/period detector
- Fast fourier transform mode
- CPU load indicator
- PWM audio output (a challenge outside the oscilloscope functionality)

Changelog:
Version 1.2 - Advanced I/O
- Added PWM audio output
- Optimized ADC through DMA use
- Frequency/period detection

Version 1.1 - RTOS, Spectrum Analyzer
- Converted system to real time OS using TI-RTOS
- Added FFT mode

Version 1.0 - Digital Oscilloscope
- Base oscilloscope functionality
- Time scale, voltage scale, and edge trigger UI
- CPU load detection
