# Multi-Link Prediction for mmWave Wireless Communication Systems

## Overview
A significant challenge encountered in mmWave and sub-terahertz systems used in 5G and the upcoming 6G networks is the rapid fluctuation in signal quality across various beam directions. Extremely high-frequency waves are highly vulnerable to obstruction, making even slight adjustments in device orientation or the presence of blockers capable of causing substantial fluctuations in link quality along a designated path. This issue poses a major obstacle because numerous applications with low-latency requirements necessitate the precise forecasting of network quality from many directions and cells.

## Proposed Method
The method proposed in this research demonstrates an avant-garde approach for assessing the quality of multi-directional connections in mmWave systems by utilizing the Liquid Time-Constant network (LTC) instead of the conventionally used Long Short-Term Memory (LSTM) technique. The method’s validity was tested through an optimistic simulation involving monitoring multi-cell connections at 28 GHz in a scenario where humans and various obstructions were moving arbitrarily.

## Results
The results with LTC are significantly better than those obtained by conventional approaches such as LSTM. The latter resulted in a test Root Mean Squared Error (RMSE) of 0.25 dB, while the former, 3.44 dB, demonstrating a 13-fold improvement. 

For better interpretability and to illustrate the complexity of prediction, an approximate mathematical expression is also fitted to the simulated signal data using Symbolic Regression.

## Reference
For more details, please refer to our publication: [MDPI](https://www.mdpi.com/2867244)
