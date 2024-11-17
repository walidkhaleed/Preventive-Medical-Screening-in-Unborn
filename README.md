# Preventive Medical Screening in Unborn

This repository contains code and documentation for extracting and analyzing fetal heartbeats from multi-electrode abdominal recordings. The project aims to ensure early detection of fetal distress and other pathological developments to improve prenatal care.

---

## Table of Contents
1. [Project Description](#project-description)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Project Structure](#project-structure)
7. [Future Work](#future-work)
8. [License](#license)

---

## Project Description

During pregnancy, fetal heartbeat monitoring plays a crucial role in identifying potential health issues. This project:
- Processes both synthetic and real-world abdominal recordings.
- Focuses on extracting maternal and fetal heartbeats.
- Aims to detect irregularities in fetal heart rates to recommend further medical investigations.

---

## Features

- **Synthetic Data Processing**: Simulate and test heartbeat extraction methods.
- **Real Data Processing**: Apply advanced signal processing techniques to extract meaningful signals from noisy abdominal recordings.
- **Noise Filtering**: Remove digestive and maternal noise to isolate fetal heartbeats.
- **Pathology Detection**: Detect irregularities and flag cases requiring additional medical evaluation.

---

## Requirements

- Python 3.8 or higher
- Jupyter Notebook
- Libraries: `numpy`, `pandas`, `scipy`, `matplotlib`, `seaborn`, and any others included in the notebook dependencies.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/preventive-medical-screening-in-Unborn.git
   cd preventive-medical-screening-in-Unborn
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## Usage

1. **Synthetic Data Processing**:
   - Open and run `processAllSynthetic.ipynb` to test heartbeat extraction algorithms.
2. **Real Data Processing**:
   - Open and run `processReal.ipynb` to apply validated methods to real-world data.
3. Analyze the results and refer to flagged cases for medical follow-up.

---

## Project Structure

```
preventive-medical-screening/
│
├── processAllSynthetic.ipynb     # Processes synthetic abdominal recordings
├── processReal.ipynb             # Processes real abdominal recordings
├── Project description Preventive_Medical_Screening_in_Unborn.pdf  # Project description
├── README.md                     # Documentation
└── requirements.txt              # Dependencies list (to be created if needed)
```

---

## Future Work

- Develop machine learning models for automating pathology detection.
- Expand the dataset to include diverse populations for better generalization.
- Optimize algorithms for faster and more robust heartbeat extraction.

---

## License

This project is licensed under the MIT License. See `LICENSE` for details.
