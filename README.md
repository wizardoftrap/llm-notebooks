# LLM Fine-Tuning & Conversion Notebooks

This repository contains Jupyter notebooks for fine-tuning large language models using different approaches and for converting trained models to LiteRT format for edge/mobile deployment.

---

## 📂 Notebooks Overview

### 🔹 Fine-tuning with Unsloth
These notebooks use the **Unsloth** framework for efficient LoRA/QLoRA fine-tuning on GPUs with reduced memory usage.

- **`functionGemma_fineTune.ipynb`**  
  Fine-tunes the FunctionGemma model using Unsloth for instruction/function-calling style tasks.

- **`qwen_8b_ocrLatex_fineTune.ipynb`**  
  Fine-tunes the Qwen-8B model using Unsloth for OCR/LaTeX or document understanding tasks.

---

### 🔹 Fine-tuning with Vanilla Hugging Face
This notebook uses standard Hugging Face `transformers`, `datasets`, and `Trainer` APIs.

- **`Fine_tune_a_language_model.ipynb`**  
  End-to-end example of fine-tuning a language model using vanilla Hugging Face without Unsloth.

---

### 🔹 Model Conversion to LiteRT
Used to convert a fine-tuned model into LiteRT format for lightweight inference on edge/mobile devices.

- **`gemma_to_litertlm.ipynb`**  
  Converts the model produced by `functionGemma_fineTune.ipynb` into **LiteRTLM** format.

## Shiv Prakash Verma
