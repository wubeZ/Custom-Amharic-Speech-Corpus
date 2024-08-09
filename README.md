# Amharic TTS Custom Dataset

## Overview

This repository contains a custom Amharic Text-to-Speech (TTS) dataset developed for research purposes. The dataset is designed to support the development and evaluation of Amharic TTS models, focusing on enhancing the naturalness and intelligibility of synthesized speech.

## Dataset Description

- **Duration:** 2 hours
- **Sampling Rate:** 44 kHz
- **Speakers:** 50 different speakers
- **Content:** Each speaker reads 15 sentences
- **Format:** Audio files are in `.wav` format, and corresponding texts are in one file in `.txt` format.
- **Quality:** The recordings were obtained under controlled conditions to ensure minimal background noise.

## Structure

The dataset is organized as follows:
```
/dataset
│
├── audio_dataset/
│ ├── 1.wav
│ ├── 2.wav
│ └── ...
│
├── transcripts/
│ ├── transcripts.txt
```

## Usage

To use this dataset, clone the repository:

```bash
git clone https://github.com/wubeZ/Custom-Amharic-Speech-Corpus.git
```

The dataset can be used for training, fine-tuning, or evaluating Amharic TTS models. Ensure you adhere to applicable license agreements and cite the dataset appropriately in your work.

## Citation

If you use this dataset in your research, please cite it as follows:

W. Zeleke, "Amharic TTS Custom Dataset," GitHub repository, [Online]. Available: [https://github.com/wubeZ/Custom-Amharic-Speech-Corpus](https://github.com/wubeZ/Custom-Amharic-Speech-Corpus). [Accessed: Aug. 5, 2024].


## Acknowledgments

This dataset was developed as part of Addis Ababa Science and Technology University research. Special thanks to the speakers who contributed their voices.
