# Reproducibility and limitations

## What is documented

The two project reports describe schematics, circuit architecture, simulation screenshots, oscillator comparisons, layout checks, mathematical models, extracted-bit analysis and a communication-system demonstration.

## Files needed for complete reproduction

- Cadence Virtuoso libraries and editable schematics
- Technology and model configuration for gpdk90; any appropriately licensed PDK resources
- Spectre and other circuit-simulation testbenches/netlists and run settings
- Original layout views and DRC/LVS/PEX logs
- CDTA oscillator simulation files, numerical models and scripts
- Raw sampled bitstreams, statistical-analysis scripts, input parameters and experiment seeds
- Communications-system simulation files and associated plots

Those source artifacts were not included in the two submitted report PDFs and have **not** been reconstructed or invented here.

## Security interpretation

Random-looking output and Shannon entropy close to one bit per symbol do not establish true randomness, min-entropy under adverse conditions or cryptographic suitability. A hardware entropy source requires additional threat modelling, robustness evaluation, health testing and appropriate validation, such as methods in NIST SP 800-90B.

## Publication policy

Publish only files the team is authorized to share; do not upload vendor PDKs, copyrighted libraries or proprietary design data without permission.
