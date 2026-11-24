# NotchLab
Interactive balanced Twin-T notch filter demonstration based on `multisim lab 2.pdf`, Problem 1.4, figures 1.12–1.15. Open index.html locally or deploy the repository root through GitHub Pages. No dependencies.

The original circuit uses R=3.16 kΩ, C=1 µF, R/2 and 2C branches and a 741 unity buffer with ±12 V supplies. The ideal transfer function is H(s)=(s²+ω₀²)/(s²+4ω₀s+ω₀²), ω₀=1/RC. Default notch is 50.36 Hz. The magnitude display is floored at −100 dB; phase at the exact null is undefined. CSV contains unclipped analytical values. Waveforms are synthetic steady-state examples, not measured ECG. No SPICE, component tolerances or clinical validation. Original report images require permission before public redistribution.
