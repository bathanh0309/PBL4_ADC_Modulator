# Introduction
Our project establishes a solid and comprehensive foundation of expertise in the field of digital signal processing and communication systems. 

We take pride in fully meeting the requirements for "ADC modulation and demodulation," delivering a solution that ensures efficient signal conversion and transmission. 
## How the System Works
An analog sine wave signal is used as input, with the following parameters:
- Amplitude: 0.75
- Frequency: 0.035 Hz
- Period: 28.5 seconds

Sampling is performed using a Zero-Order Hold block, which produces a smooth step waveform. The amplitude is reduced to 0.55 by adding a 60% width pulse.

Quantization of the signal into discrete levels.

Encoding of the quantized signal into binary form using a Uniform encoder, which produces a digital signal with 4 levels.

Modulation of the binary digital signal (0 and 1) into +1 or -1 values ​​corresponding to 0° or 180° phase.

Pass-through of a noisy channel (AWGN) is where white Gaussian noise is added, depending on the variance.

Demodulation at the receiver side helps the signal to recover binary data (0 and 1).

Evaluate performance using the Error Rate Calculation block to calculate the bit error rate (BER) which shows the influence of noise and ADC conversion on signal quality.
<div align="center">  
<a href="Final_Report.pdf" target="_blank">
     <img src="https://img.shields.io/badge/Link_Report-808080?style=for-the-badge&logoColor=white" target="_blank" /> 
</div>


https://github.com/user-attachments/assets/1de7112b-d077-4bc2-9216-d66f3e682195

