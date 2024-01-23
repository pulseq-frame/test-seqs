# ![Pulseq Logo](https://pulseq.github.io/logo.png) Test Sequences

This repository contains [pulseq](https://pulseq.github.io/) sequences that can be used to test importers, simulations etc...

In the future, expected outputs or measurements might be added.

## PyPulseq Example Sequences

All example .seq files provided by [pypulseq](https://github.com/imr-framework/pypulseq) 1.2, 1.3 and 1.4 are included. To generate them, execute `generate.py`. This script will create a new virtual python environment in which the corresponding pypulseq versions are installed to avoid modifying the python installation on your system. The output files are written to `pypulseq/<version>/`.

```
python pypulseq/generate/generate.py
```

## Single-shot Spiral TSE

The included `spiral-TSE/ssTSE.seq` is an output of [Jürgen Hennig's single-shot-spiral-TSE](https://github.com/HennigJue/single-shot-spiral-TSE). The code provides multiple sequence options, in the future more .seq files might be included for different settings.
