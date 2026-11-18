# Deadline-Aware Physiological Telemetry Scheduling

**Reproducible simulation study for mechanical circulatory support monitoring**

## Overview

This repository supports the research manuscript:

*Deadline-Aware Scheduling of Physiological Telemetry Under Network Impairments: A Reproducible Simulation Study for Mechanical Circulatory Support Monitoring.*

The study investigates deadline-aware transmission scheduling of physiological telemetry under simulated network impairments.

## Research Objectives

- Evaluate First-In, First-Out (FIFO), Earliest Deadline First (EDF), and physiology-aware scheduling strategies.
- Investigate priority-message delivery under different network conditions.
- Examine the trade-off between timely delivery of priority messages and routine telemetry continuity.
- Assess the influence of physiological signal quality on event detection and scheduling performance.

## System Architecture

The simulated monitoring architecture comprises four conceptual layers:

1. Independent pump controller
2. Edge telemetry gateway
3. Backend processing infrastructure
4. Clinical monitoring interface

The study does not implement or validate a clinical pump-control system.

## Dataset

Physiological signals are derived from selected records of the MIMIC-IV Waveform Database, version 0.1.0, hosted by PhysioNet.

Dataset DOI: https://doi.org/10.13026/a2mw-f949

The selected records are not assumed to represent patients receiving mechanical circulatory support.

Dataset access and redistribution must comply with the applicable PhysioNet terms.

## Computational Methods

The experimental workflow uses Python, NumPy, and pandas.

The research includes baseline scheduling experiments, sensitivity analyses, and exploratory physiological signal quality-control experiments.

Experimental versions and configurations will be documented separately to prevent inappropriate comparisons between implementations.

## Reproducibility

The repository is being prepared to provide:

- Simulation source code
- Experiment configuration files
- Random seeds and software dependencies
- Source record identifiers and data extraction instructions
- Derived results eligible for redistribution
- Scripts for reproducing manuscript figures and tables

**Status:** Repository initialization. The complete reproducibility package has not yet been released or independently verified.

## Limitations

This is a computational simulation study. It does not constitute clinical validation, evaluation on a physical LVAD device, or evidence of safety for deployment in medical systems.

## Citation

The manuscript citation and archived software DOI will be added when available.

## License

The software license is pending review. Dataset licensing is governed separately by the original data provider.
