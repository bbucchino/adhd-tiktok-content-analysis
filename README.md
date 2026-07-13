# Bachelor's Thesis: A Quantitative Content Analysis of Mental Health on TikTok 

## :mag: Research Question

**How is ADHD represented in TikTok content, and to what extent are these representations shaped by medicalized framings and different sources of knowledge?**

## :open_file_folder: Repository Contents

| File | Description |
|------|-------------|
| [code/final_analysis.ipynb](code/final_analysis.ipynb) | Main analysis notebook: descriptive statistics, visualizations, chi-square tests |
| [code/tiktok_api_request.ipynb](code/tiktok_api_request.ipynb) | TikTok Research API sampling and anonymization |
| [data/final_coding_sheet.csv](data/final_coding_sheet.csv) | Anonymized coding sheet (n = 400, 149 relevant) |

## :microscope: Methodology

| | |
|---|---|
| **Sample** | 400 TikTok videos, 149 included after relevance screening |
| **Hashtags** | #adhd, #adhdtiktok, #adhdlife |
| **Regions** | US, GB, AU |
| **Time window** | November 2025 – May 2026 |
| **Method** | Quantitative content analysis, 14 binary variables |
| **Statistical tests** | Chi-square with Bonferroni correction |

## :bar_chart: Key Findings

1. ADHD on TikTok is represented through everyday experiences that are nearly universally linked to ADHD (85.9%) but rarely explicitly framed as symptoms (2.7%).
2. Clinical language circulates predominantly without professional expertise (72.2%), suggesting medicalization at the conceptual level.
3. Lived experience is the dominant source of knowledge (58.4%), while professional and scientific sources remain marginal.

## :wrench: Packages

| Package | Purpose |
|---------|---------|
| `pandas` | Data loading, transformation, and analysis |
| `numpy` | Matrix operations for co-occurrence heatmaps |
| `matplotlib` | Figure creation and export |
| `seaborn` | Heatmap visualizations |
| `scipy` | Chi-square tests with Bonferroni correction |
| `requests` | TikTok API requests |

## :pencil: Note

The Python code for data collection (TikTok API) and data analysis was developed with the assistance of Claude (Anthropic). All research decisions, including variable selection, coding, selection of statistical tests and interpretation of results, were made by the author.

## :mortar_board: Author

Bai Yun Bucchino – LMU Munich, Institute of Sociology
