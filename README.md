# A toolkit for the simulation of the passage of particles through matter, in a snap!
[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/geant4)

This product includes software developed by Members of the Geant4 Collaboration ( http://cern.ch/geant4 )
Geant4 is licensed under the Geant4 Software License ( https://geant4.web.cern.ch/license/LICENSE.html )
The build files and related code in this repository itself is licensed under the MIT license, except where otherwise noted.

## Intro

This snap is an experimental approach in delivering [CERN's](https://home.cern) [Geant4](https://cern.ch/geant4) toolkit.
This snap is intended to be analogous to the [ROOT Framework](https://github.com/MrCarroll/root-snap) snap.
Similarly to the ROOT snap, a snap for Geant4 can provide a reliable, easy to use container image idealistic for new physicists and users with simpler requirements.

## Basic usage

```bash
cp /snap/geant4/current/usr/local/share/Geant4-11.0.0/examples $HOME -R
cd $HOME/examples/basic/B1
mkdir build
geant4.cmake ..
geant4.make
geant4.run ./exampleB1
```

Due to the automatic updates, ABI compatibility, and experimental nature of the snap, the build folder may need to be cleaned and the project rebuilt every so often.

## Support

This is currently an experiment, and I cannot commit to any serious support at this time.
