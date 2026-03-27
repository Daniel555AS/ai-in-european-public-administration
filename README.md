# Artificial Intelligence in European Public Administration: A Data-Driven Analysis of Adoption, Capabilities, and Impact

---

## Abstract

This work examines how Artificial Intelligence is being adopted across European 
public administrations, using the Public Sector Tech Watch (PSTW) dataset compiled 
by the European Commission's Joint Research Centre as an empirical foundation. Through 
a descriptive and exploratory analysis of 1,805 AI-related cases, I examine patterns 
of adoption across countries and regions, the distribution of AI capabilities across 
government sectors, and the impacts that AI deployments are reporting in practice. 
The findings show that AI adoption is geographically concentrated in Western and 
Northern Europe, with Learning-based systems dominating across most sectors. 
Internally-focused deployments are slightly more common than citizen-facing ones, 
yet service-related impacts are the most frequently reported, suggesting that internal 
modernization often translates into tangible improvements in public service delivery. 
Governance-related impacts, such as transparency and public participation, remain 
comparatively marginal. The analysis also reveals significant documentation gaps 
around GovTech participation, pointing to a broader limitation in how public sector 
AI initiatives are currently reported. Overall, the results offer a data-driven 
snapshot of where AI stands in European public administration today.

---

## Dimensions of Analysis

1. Primary Technology Distribution in the Dataset.

2. Distribution of AI Cases Across European Countries and Regions.

3. AI Adoption Across Government Functions: A COFOG-Based Analysis.

4. Distribution of AI Capabilities and Sectoral Deployment in European Public Administration.

5. AI Impacts in the Public Sector: Evidence on Service Delivery, Administrative Efficiency, and Governance.

6. GovTech Participation & Responsible Organisations in Public Sector AI Projects.

---

## Dataset

> European Commission, Joint Research Centre (2026): PSTW: Public Sector Tech Watch latest dataset of selected cases. [Dataset] doi: 10.2905/JRC.J1MWC9R PID: http://data.europa.eu/89h/e8e7bddd-8510-4936-9fa6-7e1b399cbd92
>
> **Retrieved:** March 4, 2026.

---

## Resources

> - [**Web Notebook**](https://daniel555as.github.io/ai-in-european-public-administration/)

---

## Project Structure

```
├── download/
│   └── ai_in_european_public_administration.zip   # Full project download
├── project/
│   ├── ai_in_european_public_administration.ipynb # Main analysis notebook
│   ├── pstw_dataset.csv                           # Dataset snapshot (March 4, 2026)
│   └── requirements.txt                           # Python dependencies
├── index.html                                     # Public web version of the notebook
└── README.md                                      # Project documentation

```
---

## Technological Stack

- ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) :  Core programming language used for all data loading, preprocessing, analysis, and visualization tasks.

- ![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white) : Cloud-based notebook environment used to develop and execute the analysis.

- ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) : Primary library for data manipulation, including cleaning, filtering, aggregation, and feature engineering.

- ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) : Interactive visualization library used to generate donut charts, bar charts, and heatmaps throughout the analysis.

- ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) : Version control system used to manage the project repository and track changes throughout development.

- ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) : Export the analysis notebook from `.ipynb` format to a static `.html` file for web publishing.

- ![Github Pages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white) : Static site hosting service used to publish the exported HTML notebook and make the analysis publicly accessible online.

- ![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white) : Document preparation system used to write and format the academic Preprint, including tables, figures, footnotes, and bibliography.

---

## Getting Started

All these steps are defined within the project's main notebook `ai_in_european_public_administration.ipynb`.

### Requirements

Installs all project dependencies listed in `requirements.txt`.

```bash
pip install -r requirements.txt
```

### Renderer Configuration

The notebook uses Plotly for visualizations. Depending on your environment, 
you may need to adjust the renderer at the top of the notebook:
```python
# Choose one option and comment out the other.

# pio.renderers.default = "colab"    # Google Colab
pio.renderers.default = "notebook"   # VS Code / Jupyter / Local
```

---

## Author

*Daniel Orlando Arias Sierra*\
2026

---