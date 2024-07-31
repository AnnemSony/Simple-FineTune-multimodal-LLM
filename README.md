# Idefics Vision-Text Model Fine-Tuning for Pokémon Cards

This repository contains code for fine-tuning the Idefics model on a Vision-Text task using a dataset of Pokémon cards. The model is trained to answer questions about images of Pokémon cards.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
  - [Setup](#setup)
  - [Data Preparation](#data-preparation)
  - [Training](#training)
- [Inference](#inference)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

To set up your environment, install the required dependencies:

```bash
pip install -q datasets
pip install -q git+https://github.com/huggingface/transformers
pip install -q bitsandbytes sentencepiece accelerate loralib
pip install -q -U git+https://github.com/huggingface/peft.git
