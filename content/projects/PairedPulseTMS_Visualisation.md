+++
title = "PairedPulse TMS Visualisation"
date = "2026-08-07"
aliases = ["paired-pulse","tms","projects"]
[ author ]
  name = "Alberto"
+++

The goal of the [**PairedPulseTMS Visualisation**](https://github.com/albertooof/PairedPulseTMS_Visualisation) package is to provide an interactive visualisation tool for inspecting and processing *paired-pulse TMS recordings* exported from LabChart.

I created and currently use the package to visually inspect individual TMS pulses, scroll through recordings, and **compare responses across different pulses and trials**. The tool makes it possible to identify and discard trials or pulses that are unsuitable for further analysis, providing a more controlled way of cleaning the raw TMS data before subsequent processing.

The package also allows me to select a **specific sub-region of the recorded waveform** for analysis. This is particularly useful for excluding artefacts or unwanted portions of the signal from the peak-to-peak amplitude calculation. By interactively selecting the relevant analysis window, the tool helps ensure that the peak-to-peak measurements are based on the appropriate part of the TMS response rather than being influenced by artefacts or other signal components.

![PairedPulseTMS_Visualization](/img/PairedPulseTMS_Visualization.gif)
