# Xenon LFP Analysis Platform

## Introduction
This is an interactive platform for analyzing bandpass filtered (1 to 2048 Hz) Local Field Potential (LFP) activity and seizure-like activity. This Graphical User Interface (GUI) is built in Python using Plotly's Dash library for interactive visualizations, this includes several features to generate summary measures, plots, trace LFP activity over time, and for people familiar with basic Python this can also serve as a boiler plate to customize, add functions and visualization based on individual researchers’ analysis requirements. We demonstrate this new python-based software tool for analysis and tracking of local field potential activity using the 3Brain MEA recording system but it can easily be adapted to any MEA recording platform. This GUI is also easily adaptable to large-scale EEG recordings and likely can provide a useful mapping tool for In-Vivo LFP activity.  Our current GUI has a particular utility for analysis of seizure-like activity but can be used for analysis of any network LFP signal. 

## Installation:
pip install xenon_lfp_analysis

## Run the Xenon LFP Analysis GUI:

After installation you can run the GUI by running the following command in the terminal:
```
$>run_lfp_analysis
```

## Documentation
https://xenon-lfp-analysis.readthedocs.io/en/latest/index.html

## PrePrint
https://www.biorxiv.org/content/10.1101/2022.03.25.485521v1
