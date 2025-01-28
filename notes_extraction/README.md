# 🎶 Sitar Audio Decomposition 🎵

A comprehensive repository for analyzing and processing sitar audio signals. This project leverages advanced audio signal processing techniques to extract musical notes, separate harmonic and percussive components, estimate fundamental frequencies, and visualize chroma features.

---

## 📂 Repository Structure

- **`audio_files/`**: Contains audio files used for analysis and processing.
- **`libfmp/`**: Libraries for Feature-based Music Processing (FMP) to aid in analysis.
- **`sitar_audio_decomposition.ipynb`**: Main notebook for signal decomposition and processing.
- **`workbook.ipynb`**: Supplementary workbook for experiments and intermediate results.
- **`requirements.txt`**: List of Python dependencies required for the project.
- **`README.md`**: You're here! Overview and instructions for the repository.

---

## ✨ Features

- **Harmonic-Percussive Source Separation (HPSS)**:
  - Isolate harmonic (melodic) and percussive (rhythmic) components of sitar recordings.
- **Fundamental Frequency (F0) Estimation**:
  - Accurate tracking of pitch over time using autocorrelation techniques.
- **Chroma Feature Extraction**:
  - Analyze harmonic components and represent them as chroma features for musical analysis.
- **Note Extraction**:
  - Convert F0 estimations to MIDI and map them to note names.

---

## 🚀 Getting Started

### Prerequisites

1. Install Python 3.8 or later.
2. Clone this repository:
   ```bash
   git clone https://github.com/chefhaider/sitar-audio-decomposition.git
   cd sitar-audio-decomposition
