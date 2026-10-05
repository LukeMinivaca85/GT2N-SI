# GT2N-SI Test Vehicle 0

## Objective

Create the first physical characterization vehicle for a
GT2N-derived stacked-nanosheet GAAFET process.

TV0 is NOT an Avalotl production chip.

Its purpose is process characterization and model calibration.

## Device structures

- NMOS GAAFET
- PMOS GAAFET
- 1-sheet characterization devices
- 3-stack nanosheet devices
- geometry sweeps
- gate-length sweeps
- nanosheet-width sweeps

## Electrical structures

- Kelvin contact structures
- contact-resistance structures
- M0 resistance structures
- M1 resistance structures
- via chains
- capacitance structures

## Logic

- inverter
- NAND2
- NOR2
- FO4 chains
- ring oscillators

## Measurements

- Id-Vg
- Id-Vd
- leakage
- threshold voltage
- subthreshold slope
- contact resistance
- metal resistance
- via resistance
- interconnect capacitance
- ring oscillator frequency

## Calibration flow

GT2N predictive model
        |
        v
TV0 fabrication
        |
        v
physical measurements
        |
        v
compact-model extraction
        |
        v
RC extraction calibration
        |
        v
standard-cell recharacterization
        |
        v
GT2N-SI silicon-calibrated PDK

## Status

PREDICTIVE / NOT FABRICATION QUALIFIED
