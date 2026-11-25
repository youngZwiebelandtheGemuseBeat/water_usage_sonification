
# Water Usage Sonification

## Description

Sonification of water usage of a tap during one day utilizing Pure Data Vanilla.

**<TODO>:** Describe the purpose, functionality and intended application
of the project here.

## Requirements

- Pure Data Vanilla
- Pd version: TBD **<TODO>:** 
- macOS with Apple Silicon (ARM64)
- Native execution without Rosetta 2

**<TODO>:** Additional platforms have not been tested.

## Installation

1. Install Pure Data Vanilla:
   https://msp.ucsd.edu/software.html
2. Clone or download this repository.
3. Install the dependencies listed in DEPENDENCIES.md.
4. Open main.pd in Pure Data.

## Usage

1. Open main.pd.
2. Configure the audio input and output devices.
3. Set the output volume to a safe level.
4. Enable DSP when required.

## Project Structure

- main.pd: Main project patch
- abstractions/: Reusable modules
- assets/: Required audio and data files
- examples/: Demonstration patches
- tests/: Test patches
- docs/: Technical documentation
- recordings/: Local recordings
- output/: Generated data

## Audio Configuration

- Sample rate: TBD
- Block size: TBD
- Input channels: TBD
- Output channels: TBD

## Development

- Prefer Pure Data Vanilla objects.
- Use relative file paths.
- Keep reusable functionality in abstractions.
- Document external dependencies.
- Keep generated files outside the source directories.

## Status

Under development.

## Authors

Luca Candussi, Stefano Motta, Melina Daniela Trummer

## License

MIT license, see LICENSE.
