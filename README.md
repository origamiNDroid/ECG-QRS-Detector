# ECG-QRS-Detector
Biomedical Sensors Course Project 1:
- Based on the Pan + Tompkins 1985 algorithm
- Sampling at 250 Hz 
- Moving Average for 38 samples

# Known Bugs
Tunable Bandpass Filter might have errors:
- Expected Center Frequency is at 11Hz, but working Center Frequency is 5.5 Hz (Possible times 2 multiplier error applied to center frequency in tunable bandpass filter's difference equation)
- Q Factor works well when set to 1.3333 (this could be better too)

