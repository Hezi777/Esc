<h1 align="center">
  <img width="260" alt="Esc" src="https://github.com/user-attachments/assets/aed0c7e1-f080-4c19-8d20-785ffd705cd5" />
  <br />
  <b>Esc</b>
</h1>

<p align="center"><b>Effect Size Calculator</b> — a PyQt6 desktop application for calculating and visualizing statistical effect sizes from CSV and Excel datasets.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.7%2B-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyQt6-GUI-green?style=for-the-badge&logo=qt&logoColor=white" alt="PyQt6">
  <img src="https://img.shields.io/badge/pandas-Data-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/matplotlib-Charts-orange?style=for-the-badge&logo=matplotlib&logoColor=white" alt="matplotlib">
  <img src="https://img.shields.io/github/license/Hezi777/Esc?style=for-the-badge" alt="License">
</p>

<p align="center">
  <a href="#about">About</a> |
  <a href="#features">Features</a> |
  <a href="#screenshots">Screenshots</a> |
  <a href="#getting-started">Getting Started</a> |
  <a href="#contributing">Contributing</a>
</p>

---

## About

Esc is a cross-platform desktop tool aimed at researchers, data analysts, and students who need to quantify the practical significance of their findings without writing custom analysis scripts. It handles the full workflow — loading a dataset, previewing it, selecting the appropriate effect size metric, generating a publication-quality chart, and exporting results — entirely through a guided GUI. The stepwise interface prevents invalid analysis configurations by unlocking controls only after each prerequisite step is satisfied.

## Features

| Area | Description |
|---|---|
| Effect size metrics | Supports Cohen's d, Cramér's V, Pearson's r, and eta-squared (ANOVA) |
| Data input | Loads CSV and Excel (.xlsx) files; previews the first 10 rows in-app |
| Visualization | Generates box plots, violin plots, strip plots, scatter plots, regression lines, hexbin plots, contingency heatmaps, and bar charts |
| Theme toggle | Switches between light and dark mode for presentation-ready output |
| Chart export | Saves plots as PNG, JPG, or PDF |
| Validation | Real-time progress bar and error dialogs guide valid analysis configuration |
| Platform support | Runs on Windows, macOS, and Linux |

## Screenshots

**Light Mode**

<img width="532" height="721" alt="v3 3 Light Mode Screenshot " src="https://github.com/user-attachments/assets/aed0c7e1-f080-4c19-8d20-785ffd705cd5" />

**Dark Mode**

<img width="536" height="719" alt="v3 3 Dark Mode Screenshot " src="https://github.com/user-attachments/assets/4421b4f7-4392-4b59-a13a-f511cd6b7e3e" />

## Tech Stack

| Layer | Technology |
|---|---|
| GUI framework | PyQt6 |
| Data handling | pandas, numpy, openpyxl |
| Statistical analysis | scipy, pingouin |
| Visualization | matplotlib, seaborn |
| Language | Python 3.7+ |

## Getting Started

### Prerequisites

- Python 3.7 or higher
- pip

### 1. Clone the repository

```bash
git clone https://github.com/Hezi777/Esc.git
cd Esc
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the app

```bash
python src/main.py
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request against `main`

## License

This project is distributed under the MIT License. See [LICENSE](LICENSE) for details.
