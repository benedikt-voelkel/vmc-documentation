+++
title = "Tar Files"
menuTitle = ""
chapter = false
weight = 5
#pre = "<b>1. </b>"
+++

### Pro versions

| Package | Version | Tar file | Tested with |
|---------|---------|----------| ------------|
| vmc | 0.1 (\*) | [v0-1.tar.gz](https://github.com/vmc-project/vmc/archive/v0-1.tar.gz) | *ROOT v6.18.00* |
| geant3 | 2.7 | [v2-7.tar.gz](https://github.com/vmc-project/geant3/archive/v2-7.tar.gz) | *ROOT 6.14.06* |
| geant4_vmc | 4.0.p1 | [v4-0-p1.tar.gz](https://github.com/vmc-project/geant4_vmc/archive/v4-0-p1.tar.gz) | *ROOT 6.14.06,<br> Geant4 10.05 (with embedded CLHEP 2.4.1.0), <br> VGM 4.4, <br> Garfield master at 07c0ec50a0d3086b3 (\*\*)* |


*(\*) this is development version, the pro version is under construction*


*(\*\*) with fixes in MR #1 in https://gitlab.cern.ch/garfield/garfieldpp*


In general, the VMC packages can be built with the Root versions which they were tested with and higher, and Geant4 VMC with the Geant4 version which it was tested with including the patches. Note that the Geant4 patches released after the Geant4 VMC tag do not appear in the table above, it is however recommended to update Geant4 with each patch release.

### Old versions

| Package | Version | Tar file | Tested with |
|---------|---------|----------| ------------|
| geant3 | 2.6 | [v2-6.tar.gz](https://github.com/vmc-project/geant3/archive/v2-6.tar.gz) | * ROOT 5.34.38 and 6.14.06* |
