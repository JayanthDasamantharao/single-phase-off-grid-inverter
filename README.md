# single phase off grid inverter
 
This paper introduces a comprehensive circuitry model for a single-phase off-grid inverter tailored for small standalone systems. Developed in MATLAB/Simulink, the model emphasizes circuitry intricacies. The inverter combines a high-frequency DC-DC step-up converter with a full bridge PI control voltage source inverter, utilizing SPWM modulation and an LC filter to create a sinusoidal output waveform. This configuration is commonly seen in small-scale commercial off-grid inverters.

The resultant model generates a 230V, 50Hz AC sine wave output from a 48V DC lead-acid battery, capable of delivering up to 1kW power. The AC sine wave output exhibits minimal Total Harmonic Distortion (THD), less than 1%, achieving near-pure sine wave characteristics. With a conversion efficiency exceeding 94%, the off-grid inverter showcases impressive performance.

Validation against a real commercial off-grid inverter confirms the alignment of the Simulink model's efficiency and THD with the commercial counterpart. This model contributes valuable insights for precise design of small to medium standalone systems and optimizing battery dimensions.
