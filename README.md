# GaN-Based Synchronous DC-DC Buck Converter

**Status: unfinished.** The project stopped at the design stage when my Erasmus+ exchange at AGH ended. The files are shared as they are: the board was not manufactured or tested.

Undergraduate project at AGH University of Krakow, Department of Power Electronics and Energy Control Systems, supervised by Prof. Robert Stala (October 2025 – January 2026).

The goal was an educational demo board where students can watch how the parts heat up as the switching frequency, load and voltage change.

## Design targets

- Synchronous buck converter with GaN transistors
- 48 V input, adjustable output (e.g. 48/12 V, 48/5 V, 48/1 V)
- Selectable switching frequency (e.g. 500 kHz – 2 MHz)
- 7.2 µH inductor, sized for 100 W at 48/12 V and 500 kHz
- Temperature sensors under the transistors, heatsink with a fan, microcontroller control and display

## What was done

- Electrical design and inductor calculation
- Component selection: GaN power stage candidates (TI LMG5200, EPC23104, EPC2152), TI F28P650DK MCU, TI TMP119 temperature sensor
- Altium schematic: power protection, gate driver, buck stage, temperature sensing
- PCB layout started

## Files

- `[01]Documents/` – project assumptions and the first design report
- `[02]Designs/[01]v1FirstDesign/` – Altium project and libraries
