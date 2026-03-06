# Security Analytics Notebooks

This project contains my hands-on AWS cloud security analytics work using Python, Jupyter, and real CloudTrail-style log data.  
The goal is to practice detection engineering, cloud telemetry analysis, and security data science techniques.

---

## 📘 CloudTrail EDA Notebook

The notebook `notebooks/cloudtrail_eda.ipynb` performs exploratory data analysis on AWS CloudTrail logs. It:

- Loads sample CloudTrail JSON from `data/cloudtrail/sample_cloudtrail.json`
- Normalizes AWS events into a pandas dataframe
- Visualizes cloud activity over time
- Summarizes top API calls and top principals
- Demonstrates early detection ideas (CreateAccessKey, AssumeRole, multi-IP behavior)

### How to Run
1. Install required libraries:
   ```bash
   pip install pandas matplotlib
   python -m notebook
   
## 🛠️ Go‑Forward Git Workflow (My Personal Notes)

```bash
# Always pull latest changes first (avoids conflicts)
git pull --rebase origin main

# Stage the files I changed
git add <path/to/file>

# Commit with a meaningful message
git commit -m "message"

# Push my changes to GitHub
git push
