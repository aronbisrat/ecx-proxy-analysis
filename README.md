# ecx-proxy-analysis

Short description: Reproducible analysis of ECX (Ethiopian Commodity Exchange) coffee proxy prices for the last 12 months (01/01/2025-12/31/2025). Notebook uses World Bank commodity price data (Pink Sheet) as a proxy for ECX behavior.

Badges:
- Run in Colab: https://colab.research.google.com/github/aronbisrat/ecx-proxy-analysis/blob/main/ecx-proxy-analysis-ethiopia-commodity-prices-las.ipynb
- Binder (launches a live environment if environment.yml or requirements.txt present)

TL;DR
This repository contains a Jupyter notebook that analyzes monthly Arabica coffee price trends, volatility, and cumulative movements relevant to Ethiopia’s commodity market. Open in Colab to run interactively.

Demo
Add a screenshot or short GIF of the main plot in assets/demo.png and update this section.

Quick start
1) Open the notebook in Colab (one click):
   https://colab.research.google.com/github/aronbisrat/ecx-proxy-analysis/blob/main/ecx-proxy-analysis-ethiopia-commodity-prices-las.ipynb

### ? Coffee Arabica Price Trend (Last 12 Months)
![Coffee Arabica Price Trend](assets/images/coffee-arabica-price-trend.png)

2) Run locally:
   git clone https://github.com/aronbisrat/ecx-proxy-analysis.git
   cd ecx-proxy-analysis
   python -m venv .venv && source .venv/bin/activate  # or `python -m venv .venv\Scripts\activate` on Windows
   pip install -r requirements.txt
   jupyter lab

Files of interest
- ecx-proxy-analysis-ethiopia-commodity-prices-las.ipynb — main analysis notebook
- requirements.txt — Python dependencies used by the notebook

Contributing
See CONTRIBUTING.md — small fixes, visual improvements, and reproducibility fixes are welcome. Look for issues labeled `good-first-issue`.

Support & discussion
- Use Issues for bug reports and feature requests

License
If you want MIT, add a LICENSE file. By default, this repo currently has no license set.

---