# LLM-s — Personal experiments with language & vision models

This repository is a personal collection of experiments and notebooks exploring language and vision architectures (GPT-2, BERT, ViT/DeiT, LSTM/RNN) along with a small personal chatbot project. Notebooks are intended to be readable, runnable, and educational.

## Repository contents

- Notebooks (top-level):
	- `bert.ipynb`
	- `GPT2 .ipynb` (note: filename contains a space)
	- `lstm.ipynb`
	- `rnn.ipynb`
	- `Vision_transformer.ipynb`
	- `DeiT.ipynb`
	- `nano_vlm.ipynb`
- Data:
	- `data/MNIST/raw/` — raw IDX MNIST files for quick experiments
- Personal chatbot:
	- `personal_chatbot/GPT2_project.ipynb`
	- `personal_chatbot/instruction-data.json`
- Misc:
	- `attn_is_all_u_need.png`

## Quick start

1. Create and activate a virtual environment (recommended):

	 python -m venv .venv
	 source .venv/bin/activate

2. Install common packages used across the notebooks (example):

	 pip install --upgrade pip
	 pip install jupyterlab notebook numpy pandas matplotlib torch torchvision transformers datasets tqdm

3. Launch Jupyter and open the notebook you want to run:

	 jupyter lab

Notes:
- Many notebooks are exploratory; run them cell-by-cell and read the inline commentary.
- For training or fine-tuning, a GPU (CUDA) will significantly speed up runs. Notebooks will run on CPU but more slowly.

## Personal chatbot

Open `personal_chatbot/GPT2_project.ipynb` for a guided example of using a GPT-2 model for a small chatbot, including tokenizer setup and fine-tuning data format (`instruction-data.json`).




