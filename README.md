# Multimodal Image Understanding Pipeline

This project implements a multimodal vision-language pipeline using state-of-the-art Transformer models for image understanding and reasoning.

## Features

- Image Captioning using BLIP
- Visual Question Answering (VQA) using BLIP
- Text-based Reasoning using FLAN-T5
- End-to-end multimodal inference pipeline

## Pipeline

1. Input Image
2. Generate Caption using BLIP
3. Ask Question using BLIP-VQA
4. Generate Explanation using FLAN-T5
5. Return Final Interpretable Output

## Models Used

| Model | Purpose |
|---------|---------|
| BLIP | Image Captioning |
| BLIP VQA | Visual Question Answering |
| FLAN-T5 | Explanation Generation |

## Installation

```bash
pip install -r requirements.txt
```

## Requirements

```text
torch
transformers
accelerate
sentencepiece
pillow
matplotlib
```

## Usage

Open the notebook:

```bash
jupyter notebook notebooks/models_and_pipeline.ipynb
```

Update the image folder path and run all cells.

## Example Workflow

Input Image → Caption Generation → VQA → Reasoning → Final Explanation

## Applications

- Image Understanding
- Visual Content Analysis
- Explainable AI
- Vision-Language Research
- Educational Demonstrations


