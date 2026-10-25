# Learning notes

# Learning notes – GPT from Scratch

## Day 0 · Sat, Oct 24, 2026 · Setup (2 h)

**Done**
- Created the public repo `gpt-from-scratch` with README, MIT license and folders (`src/`, `notebooks/`, `data/`)
- Set up a Python 3.12 environment (`gpt`) on my Mac with PyTorch, NumPy, Matplotlib, W&B and Jupyter
- Connected Google Colab to a free NVIDIA Tesla T4 GPU (16 GB): `torch.cuda.is_available()` → True
- Mounted Google Drive for checkpoints (`MyDrive/gpt-from-scratch/checkpoints`)
- Set up Weights & Biases and logged a first test run
- Saved `notebooks/00_setup.ipynb` from Colab to GitHub
- Setup notebook: [Open in Colab](https://colab.research.google.com/github/Tarun7981448226/gpt-from-scratch/blob/main/notebooks/00_setup.ipynb)

**Learned**
- Git workflow: save → `git add` → `git commit` → `git push` (and `git pull` after editing on GitHub/Colab)
- `git mv` moves a file and records the move in Git (I used it to fix a folder name that had spaces in it)
- `python -m pip` installs into the active environment
- Never commit API keys to a public repo

**Next:** Day 1, Karpathy's micrograd (backpropagation from scratch)