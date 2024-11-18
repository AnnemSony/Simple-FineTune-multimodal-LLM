# Vision-Text Model Fine-Tuning for Pokémon Cards

This repository contains code for fine-tuning the Idefics model on a Vision-Text task using a dataset of Pokémon cards. The model is trained to answer questions about images of Pokémon cards.


```bash
pip install -q datasets
pip install -q git+https://github.com/huggingface/transformers
pip install -q bitsandbytes sentencepiece accelerate loralib
pip install -q -U git+https://github.com/huggingface/peft.git
