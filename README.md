# Pedicle Screw Simulator

A pedicle screw placement planning simulator built as module for 3D Slicer.
Supports placement of screws on CT images in any file format supported by VTK
(DICOM, Nifti, Nrrd, MHA, etc). This repository is a fork of a fork of the original
module designed by the Sunnybrook Research Institute in Toronto.


## Installation

1. Download and install [3D Slicer v4.10.2](https://slicer.kitware.com/midas3/folder/274) using one of the following links:
    - [Linux](https://slicer.kitware.com/midas3/download/item/435293/Slicer-4.10.2-linux-amd64.tar.gz)
    - [MacOS](https://slicer.kitware.com/midas3/download/item/433773/Slicer-4.10.2-macosx-amd64.dmg)
    - [Windows](https://slicer.kitware.com/midas3/download/item/433684/Slicer-4.10.2-win-amd64.exe)
2. Download the contents of this repository using one of the following methods:
    - Using Git in a terminal: `git clone --branch custom https://github.com/roozbehshams/PedicleScrewSimulator`
    - Via the releases page (extract the contents): https://github.com/roozbehshams/PedicleScrewSimulator/releases/tag/v1.0
3. Install the module in 3D Slicer:
    1. Launch 3D Slicer
    2. Open the **Edit/Application Settings**
    3. Switch to the **Modules** menu item in the left navigation
    4. In the **Additional module paths**, *Add* a path to the `PedicleScrewSimulator` folder inside the previously downloaded path (`PedicleScrewSimulator/PedicleScrewSimulator`)
    5. Click **OK**, 3D Slicer should prompt to relaunch the application in order to correctly load the module

> Note: In step *3.4*, the correct path to be added must be to the folder called `PedicleScrewSimulator` which is situated inside
> the cloned/extracted directory of the same name. For example: `/home/JohnDoe/PedicleScrewSimulator/PedicleScrewSimulator`.

## Usage

1. Load the module called `Training/Custom Pedicle Screw Simulator`
