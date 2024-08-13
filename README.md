# Movement_Detector_24GHz_Radar
A 24 GHz radar sensor detects movements and sends detected signal to bandpass filter.
The 4th order Bandpass filter gives amplified signal as the output which in-turn is sent to the ADC.
PSOC calculates FFT of ADC data and sends it to MATLAB.
CFAR is used to set a threshold with which the probability of false alarm reduced.
