# CSGY6923-Project
Project: Scaling Laws for Language Models Trained on Symbolic Music Data

## Overview

This project investigates neural scaling laws in the context of symbolic music generation. We train transformer-based language models on ABC notation music data to analyze how model performance scales with parameters, compute, and dataset size.

## Repository Structure

The `project.ipynb` notebook contains the complete pipeline:

- **Data Preprocessing**: Scripts for downloading, converting, and tokenizing symbolic music data
- **Configuration**: Hyperparameters and architecture specifications for all tested models
- **Model Training**: Implementation based on nanoGPT with configurable architectures
- **Evaluation**: Loss computation and scaling law analysis
- **Sample Generation**: Music generation from trained models

Note: The notebook might not render directly on GitHub. Just download it and open it manually to see my work.

## Installation

Regardless, everything on the project.ipynb file should already contain all of the necessary setup, but I will provide the necessary command line installations below:

### Prerequisites

Ensure you have Python 3.8+ installed, then install the required dependencies:

```
pip install -r requirements.txt
```

### System Dependencies

The project requires abcmidi for ABC notation processing. Install it using:

```
apt-get install -y abcmidi
```
