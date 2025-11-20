# Traffic Prediction and Management System (TPMS)

This repository contains a traffic congestion prediction and management project built with Python.

Contents:
- `TPMS/` - application and model code
  - `train_model.py` - training script
  - `traffic_app.py` - Streamlit app
  - `test.py` - quick tests/examples
  - `data/` - dataset (CSV)
  - `models/` - trained model artifacts

Quick setup:
1. Create and activate a virtual environment (recommended):

   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1
   pip install -r requirements.txt
   ```

2. To run the Streamlit app:

   ```powershell
   streamlit run TPMS\traffic_app.py
   ```

Git / push instructions (replace `<your-repo-url>` with the HTTPS remote URL):

```powershell
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```

If you don't have a remote repo yet, create one on GitHub and copy the repository URL, or tell me the name and I can help with steps.
