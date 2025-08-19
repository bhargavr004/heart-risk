# Environment Setup — Heart Disease Risk Project

## Requirements
- Python 3.8 or higher
- Git
- (Optional) VS Code or PyCharm

## Create virtual environment (macOS/Linux)
1. `python3 -m venv .venv`
2. `source .venv/bin/activate`
3. `pip install --upgrade pip`
4. `pip install -r requirements.txt`

## Create virtual environment (Windows PowerShell)
1. `python -m venv .venv`
2. `.venv\Scripts\Activate.ps1`
3. `python -m pip install --upgrade pip`
4. `pip install -r requirements.txt`

## Verify installation
`python src/verify_env.py`

## Git workflow
- Branch from `develop` for new features: `git checkout -b feature/<name>`
- Push and open PR to `develop`, merge after review.
- Tag releases on `main`.

## Datasets
Place raw datasets under `data/raw/<source>/`. Keep processed files under `data/processed/`.

## Notes on data privacy
Do not upload or commit private health information (PHI) or files containing personally identifiable information.

## Troubleshooting
- If imports fail, ensure the virtual environment is activated.
- If `pip` install fails for some packages, update pip: `python -m pip install --upgrade pip setuptools wheel`.
