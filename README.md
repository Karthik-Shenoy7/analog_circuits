# Analog Circuits Odyssey

Course reference and simulation platform for 25ECE211 Analog Electronic Circuits.

Independent student project by Karthik Shenoy (karthikshenoy17@gmail.com). Strictly not affiliated with, endorsed by, or connected to NMAM Institute of Technology (NMAMIT) or Nitte (Deemed to be University).

## Overview

The platform provides 10 laboratory simulations, a small-signal circuit studio with 31 branch variations, a searchable table of 31 formulas, and a worked problem solver for course 25ECE211.

- Unit 1: Diode Waveshaping and BJT Analysis (clippers, clampers, 3D carrier transport, DC load line, small-signal re model).
- Unit 2: MOSFET Physics and Biasing (3D NMOS chamber with channel inversion and pinch-off, ID-VDS and ID-VGS curves, DC load line).
- Unit 3: Small-Signal Transistor Amplifiers (Common-Source, Source Degeneration, Common-Drain, and Common-Gate stages with frequency response).
- Unit 4: Differential and Multistage Amplifiers (MOS differential pair, CMRR, current mirrors, and power amplifier stages).
- Unit 5: Feedback Amplifiers and Oscillators (feedback topologies, Barkhausen criterion, RC phase-shift, Wien bridge, Colpitts, and Hartley oscillators).
- Circuit Studio: Interactive schematic viewer and parameter derivation calculator for 10 core circuit topologies with 31 branch modifications.
- Formulas Reference: Searchable KaTeX reference table with circuit schematics and derivations.
- Worked Problem Solver: Step-by-step solutions for exam questions with adjustable numerical parameters.

## Running Locally

Run a local HTTP server from the project directory:

```bash
python -m http.server 8080
```

Open a browser at:
http://localhost:8080

## Testing

Run the test suite using Python and Playwright:

```bash
python tests/qa.py
```
