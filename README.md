# EEG-Based Fatigue & Attention Tracker

## Overview
This project aims to build a real-time system to monitor and predict human mental states like fatigue, distraction, or focus using EEG data. The system is designed to assist in cognitive safety applications such as driver alertness, workspace focus, and brain-computer interfaces.

## Features
- EEG signal acquisition (via simulated logs or BrainLink)
- Preprocessing: noise filtering, FFT, signal smoothing
- Real-time prediction of mental states
- Logging and training for improving model accuracy

## Tech Stack
- Python 3
- NumPy, Pandas, Matplotlib
- SciKit-learn for ML models
- Custom EEG signal parser and logger

## Status
Initial prototype built using synthetic EEG logs. Model trained to detect fatigue with ~70% accuracy on test data.

## Future Roadmap
- Switch to real EEG hardware input (BrainLink or Muse)
- Train deeper models using real-time labeled data
- Integrate with StarkOS and respond to attention drops

## Author
**M P Anwar Baba** — Building AI that listens to the brain.