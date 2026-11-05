# ADC / DAC Educational Simulator

**Stable release:** 2.0  
**Author:** Santiago Borrero Ortiz  
**Copyright:** © 2026 Santiago Borrero Ortiz

A Python educational application for visualizing analog-to-digital conversion
(ADC), digital-to-analog conversion (DAC), and a complete digital
transmission and reception chain.

## Features

- **ADC workflow:** anti-aliasing, sampling, quantization, and binary encoding.
- **DAC workflow:** decoding, D/A conversion, zero-order hold (ZOH), and filtering.
- **Complete workflow:** transmitter, ideal channel, receiver, and signal reconstruction.
- Selectable resolution: 4, 8, and 12 bits.
- Adjustable signal frequency and sampling frequency.
- Manual and automatic sampling demonstrations.
- Aliasing demonstration by bypassing the anti-aliasing filter.

## Requirements

- Python 3.9 or later.
- NumPy
- Matplotlib
- SciPy

Install dependencies:

```bash
python -m pip install -r requirements.txt
```

## Run

```bash
python simulador_adc_dac_v2_0.py
```

## Interface language

The graphical user interface is in English. Source-code comments and
development notes may remain in Spanish.

## Licenses

This project uses two separate licenses:

- **Source code:** [MIT License](LICENSE).
- **Documentation and teaching materials:** [Creative Commons
  Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/),
  see [LICENCIA-DOCUMENTACION.txt](LICENCIA-DOCUMENTACION.txt).

The MIT license applies to the source code. The CC BY 4.0 license applies
to documentation and teaching materials; it does not replace the code license.

## Release notes — 2.0

Version 2.0 is the first stable release of the simulator. It consolidates
the ADC, DAC, and complete transmission/reception workflows, including
manual and automatic sampling, quantization visualization, binary encoding
and decoding, and final signal reconstruction.

The final reconstruction view highlights the filtered reconstructed signal,
while retaining the original waveform and the ZOH output for comparison.

## Project status and contributions

This is an initial educational version of the ADC/DAC simulator. It is a functional starting point, but it is not a finished product. There is plenty of room for improvement, new features, bug fixes, and alternative ways to visualize and explain digital signal processing concepts.

**Contributions and suggestions are very welcome!**

Whether you are a teacher, student, developer, or simply interested in electronics and digital communications, feel free to explore the project, report issues, suggest improvements, or contribute code.

The goal is to make this simulator a better educational tool through collaboration and shared ideas.

**Let's improve it together!**

## Copyright

Copyright (c) 2026 Santiago Borrero Ortiz.
