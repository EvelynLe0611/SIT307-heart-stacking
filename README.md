# SIT307 HD Task - Heart Attack Prediction with Stacking

Reproduction and improvement of: M. Bhagat, A. Sharma and P. Agarwal, "An efficient stacking-based
ensemble technique for early heart attack prediction", Multimedia Tools and Applications, 2025.

## Files
- `heart_attack_project.ipynb` - all the code (Part 1 reproduction, data checks, Part 2 method)
- `data/heart.csv` - the Kaggle dataset used in the paper (1025 rows)
- `data/uci/` - the original UCI heart disease files for 4 hospitals
- `requirements.txt` - package versions I used

## How to run
1. Install Python 3.11 or newer.
2. Install the packages:
   ```
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```
   jupyter notebook heart_attack_project.ipynb
   ```
4. Click **Kernel > Restart & Run All**. It takes about 10-15 minutes.

All tables are saved in `results/` and all figures in `figures/`. The random seeds are fixed,
so running it again gives the same numbers.

## Data sources
- Kaggle: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset
- UCI: https://archive.ics.uci.edu/dataset/45/heart+disease