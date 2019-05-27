# AgroMo project

## Introduction

AgroMo is an Integrated Assessment and Modelling software that integrates the a CERES based crop model, the BiomeBGC-MuSo biogeochemical and a simple agro-economical model in order to support decision makers at multiple scales.

## AgroMo User Interface

A graphical user interface (GUI) has been developed for providing easy and user freindly access to the functions of the AgroMo system. When lunching the AgroMo App the user meets the AgroMo Base form first.

### AgroMo Base

![alt text](basegui.png "AgroMo Base")

- [ ] You may choose the main directory where your data files are located (in a fixed subdirectory system) by clicking the [CHOOSE] button
- [x] You may go to the site specific component by clicking the [SITE] button
- [x] You may create plots of the simulation results after clicking the [PLOT] button
- [ ] You may create, open, edit and save your input files with the [INPUT FILE MANAGER] after clicking the corresponding button


### AgroMo Site

![alt text](sitegui.png "AgroMo Site")
- [x] The dropdown menus display the content of the corresponding directories within the input folder:
  - INI file (extension: .ini): ./input/initialization/
  - WEATHER file (extension: .wth): ./input/weather/site/
  - SOIL file (extension: .soi): ./input/soil/site/
