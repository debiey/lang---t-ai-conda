# Lang-&-t-ai-conda

**AI Training Lab (Miniconda Version)**  
A complete beginner-friendly training ground for learning Artificial Intelligence on Windows.

This lab is designed so you can return to it anytime — during the summer program and long after.

---

## Who is this for?
- Complete beginners (no prior Python or AI knowledge required)
- Students using **Windows** laptops
- Anyone who wants a clear, step-by-step path from zero to building and training AI models

## What you will learn
- Python fundamentals for AI
- Working with data (NumPy & Pandas)
- Data visualization
- Classical Machine Learning (scikit-learn)
- Neural Networks & Deep Learning (TensorFlow/Keras)
- Building, training, evaluating, and improving models
- Mini projects you can showcase

---

## Quick Start (Windows)

1. Install **Miniconda** (see `SETUP_WINDOWS.md`)
2. Open **Anaconda Prompt** or PowerShell
3. Navigate to this folder
4. Create and activate the environment:

```powershell
conda env create -f environment.yml
conda activate lang-t-ai
```

5. Launch Jupyter Lab:

```powershell
jupyter lab
```

6. Open the notebooks in the `notebooks/` folder and start with `01_python_basics.ipynb`

---

## Lab Structure

```
Lang-&-t-ai-conda/
├── README.md
├── SETUP_WINDOWS.md          ← Detailed Windows installation guide
├── environment.yml           ← Conda environment (recommended)
├── notebooks/                ← All learning materials
│   ├── 01_python_basics.ipynb
│   ├── 02_numpy_fundamentals.ipynb
│   ├── 03_pandas_data_handling.ipynb
│   ├── 04_data_visualization.ipynb
│   ├── 05_classical_ml.ipynb
│   ├── 06_intro_neural_networks.ipynb
│   ├── 07_image_classification.ipynb
│   └── projects/
├── data/                     ← Sample datasets
├── models/                   ← Saved models go here
├── scripts/                  ← Helper scripts
└── assets/                   ← Images and resources
```

---

## How to use this lab as a training ground

- Work through the notebooks in order
- Do all the exercises (marked with **Your Turn**)
- Experiment — change values, break things, fix them
- Save your trained models in the `models/` folder
- Come back anytime to revise or continue from where you stopped

---

## Need Help?

Check the `SETUP_WINDOWS.md` file first.  
Most common Windows issues are already documented there.

---

**Happy Learning!**  
Lang & T AI Summer Program
