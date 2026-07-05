[![GitHub (pre-)release](https://img.shields.io/github/release/vasilsaroka/ClarStructureFinder/all.svg)](https://github.com/vasilsaroka/ClarStructureFinder/releases)
[![GitHub Downloads (all assets, latest release)](https://img.shields.io/github/downloads-pre/vasilsaroka/ClarStructureFinder/latest/total?label=downloads%20latest)](https://github.com/vasilsaroka/ClarStructureFinder/releases)
[![GitHub Downloads (all assets, specific tag)](https://img.shields.io/github/downloads/vasilsaroka/ClarStructureFinder/v1.0.0/total?label=downloads%20v1.0.0)](https://github.com/vasilsaroka/ClarStructureFinder/releases/tag/v1.0.0)
[![Github All Releases](https://img.shields.io/github/downloads/vasilsaroka/ClarStructureFinder/total?label=downloads%20all)](https://github.com/vasilsaroka/ClarStructureFinder/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Support TBpack](https://img.shields.io/static/v1?label=support&message=5$&color=green&style=flat&logo=paypal)](https://paypal.me/vasilsaroka?locale.x=en_GB)


# ClarStructureFinder
Wolfram Mathematica graphical user interface (GUI) for building planar polycyclic aromatic hydrocarbons and analyzing their resonance valence bond structures with support of import from and export into .XYZ files

## Requirements
The code was developed and tested under
 - OS: Microsoft Windows 11 Home
 - Mathematica 14.2.1 for Microsoft Windows (64-bit) (March 17, 2025).

## Installation
This repository contains only a notebook with core functions in `.../Core` folder.

The GUI distributed in [releases]() does not require installation. It can be run as a regular Mathematica Notebook (.nb), which contains a dynamical content and requires enabling upon the start:
<p align="center">
<img src="https://github.com/vasilsaroka/ClarStructureFinder/blob/main/Demo/Enable_Dynamics.png" alt="Enable_Dynamics_button" width="400"/>
</p>
Once dynamical content is enabled, the GUI must be active and responsive out-of-the-box.

## Demo
The work with GUI starts from building a planar graph of a hydrocarbon molecule on a canvas by specifying position of atoms with a mouse click anywhere on the canvas. This is the *Building mode* regime:
<p align="center">
<img src="https://github.com/vasilsaroka/ClarStructureFinder/blob/main/Demo/ClarStructureFinder_welcome_screen.png" alt="Welcome_screen" width="400"/>
</p>

The built graphs can be analysed in two other regimes: *Gallai-Edmonds' structure* and *Clar's structure*. The idea behind this approach is explained in detail in the LinkedIn article [50 years of Clar's aromatic sextet... and no automation yet?](). 

As a quick start, let us build and analyse in the *Clar's structure* regime a Kekulene molecule studied in [J. Am. Chem. Soc. **141**, 15488–15493 (2019)](https://doi.org/10.1021/jacs.9b07926):
<p align="center">
<img src="https://github.com/vasilsaroka/ClarStructureFinder/blob/main/Demo/ClarStructureFinder_demo.gif" alt="Clar_Structure_regime" width="400"/>
</p>

The GUI supports import of carbon skeletons (hydrogens are stripped automatically) from .XYZ structure files straight into the canvas, thereby allowing one to avoid manual building. On the other hand, it is possible to export graphs from the canvas into a .XYZ structure file with automatic hydrogenation of the edges. These two tools can be used interoperably within the GUI.

## Supporting the project
Consider becoming a paying user on this project. This is how I earn a living, as I am directly user-supported. Moreover, you will get an exclusive content and an early access to new releases. Anyone [making a donation](https://paypal.me/vasilsaroka?locale.x=en_GB) is entitled to request a version without watermarks. If you like the free app, you will love the paying user-only version. Such donations are really appreciated for keeping this project going. 
