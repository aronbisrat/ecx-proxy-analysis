# Contributing to ecx-proxy-analysis

Thanks for your interest! We welcome contributions of all sizes.

Run the notebook locally
1. Clone the repo:
   git clone https://github.com/aronbisrat/ecx-proxy-analysis.git
   cd ecx-proxy-analysis
2. Create environment (pip):
   python -m venv .venv && source .venv/bin/activate
   pip install -r requirements.txt
3. Start Jupyter Lab or Notebook:
   jupyter lab

How to contribute
1. Fork the repository
2. Create a branch: git checkout -b fix/meaningful-description
3. Make changes, run the notebook cells, and ensure results reproduce
4. Commit and push your branch, then open a Pull Request with a clear description

Reporting issues
- Use the issue template when filing bugs. Include the notebook filename, cell number (if applicable), and full traceback or screenshot.

Good first contributions
- Add a screenshot or GIF to assets/ and update README
- Add a Binder badge and confirm the notebook loads
- Create a short 'Data sources' section in the notebook describing columns and where the data came from

Code style
- Keep changes small and focused
- Add comments and improve documentation inside notebook cells

Communication
- Be respectful and follow a Code of Conduct. If you'd like, we can add a CODE_OF_CONDUCT.md file next.
