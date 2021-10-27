# OFDM Explained

[![View <File Exchange Title> on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/####-file-exchange-title)  

OFDM explained: Cyclic prefix, equalization, synchronization and oversampling
Orthogonal Frequency Division Multiplexing (OFDM) is the primary digital modulation technique used by modern wireless communications systems such as 5G cellular and WiFI. The advantages of OFDM over previously used techniques like single carrier QAM are primarily related to the ability to support high speed bit data rates with a simple receiver design.

Equalization and synchronization are both simplified by the use of FFT based OFDM with a cyclic prefix (CP).
The code included below first explains basic OFDM, then shows how to augment OFDM with a cyclic prefix.
The latter case allows easy use of OFDM in an environment that includes a nonideal channel and unknown propagation delay.
In the last section of the code, we illustrate how OFDM+CP can be modified to efficiently yield an oversampled waveform out of the modulator.
For more information, a conceptual explanation of OFDM can be seen at [What Is OFDM?](https://www.mathworks.com/discovery/ofdm.html)

MathWorks&reg; toolboxes such as 5G Toolbox&trade; include customized OFDM functions that conveniently support data packing and customization of waveforms as prescribed in each of those protocols. 5G OFDM is described at [Generate OFDM modulated waveform - nrOFDMModulate](https://www.mathworks.com/help/5g/ref/nrofdmmodulate.html). In addition, basic OFDM modulation and demodulation functions are built into the Communications Toolbox&trade;.

No setup is required. Just run ofdmpub_final from the MATLAB command line or from the editor toolstrip. For best experience, open the the file in the MATLAB editor and run a section at a time while observing outputs from that section. If you open the file in the MATLAB editor, you can also take advantage of several embedded live editor controls to enable/disable equalization, as well as to tweak parameters like time offset and observe impact on the algorithm.

This example requires MATLAB release R2020b or newer and the [Communications Toolbox](https://www.mathworks.com/products/communications.html).

The license for OFDM Explained is available in the LICENSE.TXT file in this GitHub repository.

## Community Support
[MATLAB Central](https://www.mathworks.com/matlabcentral)

Copyright 2021 The MathWorks, Inc.
