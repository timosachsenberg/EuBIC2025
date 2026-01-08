# EuBIC2026 Winter School

Educational Jupyter notebooks for the EuBIC 2026 Winter School, teaching proteomics data analysis workflows using PyOpenMS.

## Notebooks

| Notebook | Topic | Description |
|----------|-------|-------------|
| **Task 0** | Prerequisites | Python, NumPy, pandas, and mass spectrometry fundamentals (optional) |
| **Task 1** | Peaks | Protein digestion, MS1 visualization, isotope patterns, TIC |
| **Task 2** | Identification | Peptide database search, fragment spectra, scoring, mirror plots |
| **Task 3** | Quantification | Feature detection with Biosaur2, ID mapping, visualization |

**New to Python or mass spectrometry?** Start with Task 0 to learn the fundamentals.

**Quick Start:** Click the "Open in Colab" badge at the top of any notebook to run it directly in Google Colab without local installation.

## Setup

### Prerequisites
- Python 3.8 or higher
- pip or conda package manager

### Installation

1. Clone this repository:
```bash
git clone https://github.com/timosachsenberg/EuBIC2026.git
cd EuBIC2026
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

Or using conda:
```bash
conda create -n eubic2026 python=3.10
conda activate eubic2026
pip install -r requirements.txt
```

### Running Jupyter

Start Jupyter Lab:
```bash
jupyter lab
```

Or start classic Jupyter Notebook:
```bash
jupyter notebook
```

## Repository Structure

```
EuBIC2026/
├── notebooks/
│   ├── EUBIC_Task0_Prerequisites.ipynb  # Python & MS fundamentals
│   ├── EUBIC_Task1_Peaks.ipynb          # Digestion & MS1 data
│   ├── EUBIC_Task2_ID.ipynb             # Peptide identification
│   └── EUBIC_Task3_Quant.ipynb          # Quantification
├── data/                                 # Sample data files
└── requirements.txt                      # Python dependencies
```

## Usage

1. Navigate to the `notebooks/` directory
2. Open notebooks in order (Task 0 → Task 1 → Task 2 → Task 3)
3. Each notebook includes collapsible sections for beginners and advanced users

## License

See [LICENSE](LICENSE) file for details.
