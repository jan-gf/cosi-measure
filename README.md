# COSI Measure

![COSI Measure](res/img/setup-overview.jpg)

COSI Measure is an open-source, multipurpose 3-axis robotic system designed for operation in large volumes. It can be equipped with various field mapping probes for static or dynamic measurements, including electromagnetic and temperature sensing. Experimental evaluations have confirmed its submillimeter accuracy, reproducibility, and minimal backlash. With potential upgrades, it can be adapted for other applications requiring precise, repeatable submillimeter movements.


## Table of Contents

- [System specifications](#system-specifications)
- [Versions and Branches](#versions-and-branches)
- [Rebuild your own COSI Measure](#rebuild-your-own-cosi-measure)
- [Contacts](#contacts)
    - [Known builds](#known-builds)
- [Contributors alphabetical order](#contributors-alphabetical-order)
- [Publications](#publications)
- [Acknowledgments](#acknowledgments)
- [License and Liability](#license-and-liability)



## System specifications

- Dimension: (80x90x105)cm³
- Working volume: (53x53x64)cm³
- Precision: positioning error <1mm
- Max load: ~20kg
- Applied force: 896N (91kg)
- Standalone system
- Inductive limit switches
- Emergency Stop
- Open Source Software (Python)
- Estimated material costs: ~2000€

More photos and videos can be found on opensourceimaging.org: <https://www.opensourceimaging.org/project/cosi-measure/>

## Versions and Branches

You're currently viewing the `2.1` branch, showing ongoing development on `v2.1.*` of the COSI Measure system.\
New versions are developed in dedicated feature branches and then merged to `main`.

The latest stable release is [v2.0](https://github.com/opensourceimaging/cosi-measure/releases/tag/v2.0).

For older, please check out the [releases overview](https://github.com/opensourceimaging/cosi-measure/releases/).

The changes between versions are summarized in the respective release notes and documented in the [CHANGELOG](CHANGELOG.md) document.

## Rebuild your own COSI Measure

How to build the hardware: [doc/README.md](doc/README.md)

We propose to use the software in this repository: 

## Contacts

General contact:
Name | Email | Institution | COSI Measure Applications
-----|-----|-----|-----|
Lukas Winter | <lukas.winter@ptb.de> | Physikalisch-Technische Bundesanstalt (PTB), Berlin, Germany | Magnetic field mapping of MR magnets, implant safety measurements, RF field mapping of RF coils using time-domain H- and E-field sensors, Measurements within an MR scanner, 3D printing

![COSI Measure Builds](Publications/cosi_measure_builds.jpg)

### (Known) builds

Name | Email | Institution | COSI Measure Applications
-----|-----|-----|-----|
Haopeng Han | <haopeng.han@mdc-berlin.de> | Max-Delbrück Center for Molecular Medicine, Berlin, Germany | Temperature and RF field mapping of RF coils
Tom O'Reilly | <t.o_reilly@lumc.nl> | Leiden University Medical Center (LUMC), Leiden, Netherlands | Magnetic field mapping of low field MR magnets
Benjamin Menküc | <benjamin.menkuec@fh-dortmund.de> | University of Applied Sciences, Dortmund, Germany | Magnetic field mapping of low field MR magnets
Mark Bason | <M.Bason@sussex.ac.uk> | Quantum Systems and Devices, University of Sussex, Falmer, England | Magnetic field measurements
Wolfgang Kilian | <Wolfgang.Kilian@ptb.de> | Physikalisch-Technische Bundesanstalt (PTB), Berlin, Germany | 3D printing of phantoms
Julia Pfitzer  | <jpfitzer@tugraz.at> | Technische Universität Graz, Graz, Austria | Magnetic field measurements

## Contributors (alphabetical order)

Nils Allek, Mark Bason, Jan Gregor Frintz, Haopeng Han, Amjad Kasabashy, Wolfgang Kilian, Ilia Kulikov, Benjamin Menküc, Tobias Mohr, Reiner Montag, Tom O'Reilly, Julia Pfitzer, David Shiers, Berk Silemek, Karl Stupic, Lukas Winter

## Publications

If you find this useful in your work, please cite:
[H. Han, R. Moritz, E. Oberacker, H. Waiczies, T. Niendorf and L. Winter, "Open Source 3D Multipurpose Measurement System with Submillimetre Fidelity and First Application in Magnetic Resonance", Scientific Reports, 7:13452, 2017](https://nature.com/articles/s41598-017-13824-z)

## Acknowledgments

This work is supported by the Open Source Imaging Initiative (OSI²), <https://www.opensourceimaging.org/project/cosi-measure/>

The project (21NRM05) has received funding from the European Partnership on Metrology, co-financed by the European Union's Horizon Europe Research and Innovation Programme and by the Participating States.

## License and Liability

The content in this repository is licensed under the CERN Open Hardware Licence Version 2 - Weakly Reciprocal, please see [LICENSE](LICENSE) for details and also check the [DISCLAIMER](DISCLAIMER.pdf).
