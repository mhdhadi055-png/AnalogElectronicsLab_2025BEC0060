# Experiment 01 – NMOS Characterization

## Aim

To characterize an NMOS transistor using Cadence Virtuoso and Spectre simulation.

## Design Specifications

- NMOS Width (W): 1 µm
- NMOS Length (L): 100 nm
- VGS sweep: 0 V to 1.2 V

## Circuit Description

An NMOS test circuit was implemented in Cadence Virtuoso. VGS and VDS are applied through voltage sources.

## Simulation Procedure

DC analysis was performed using Cadence Virtuoso / Spectre.
The gate-source voltage was swept to obtain the transfer characteristic.
Multiple VGS values were used to obtain the VDS output characteristics.

## Results

The VGS transfer characteristic shows increasing drain current with increasing VGS.

The VDS output characteristics show higher drain current for higher VGS values.

The DC operating point was evaluated at:

- VDS = 0.6 V
- VGS = 1 V

The reported threshold voltage is approximately 211.47 mV.

## Observations

The drain current remains very small at low VGS and increases significantly as VGS increases.

For the output characteristics, higher VGS produces higher drain current, while the curves become less steep as VDS increases.

## Conclusion

The NMOS device was successfully characterized using Cadence Virtuoso / Spectre simulation. The transfer characteristics, output characteristics, simulation setup, and DC operating point were obtained.
