# 🧠 Fine-Tuning DeepSeek-R1 for Medical Reasoning with Unsloth

This project fine-tunes the `DeepSeek-R1-Distill-Llama-8B` language model using the [Unsloth](https://github.com/unslothai/unsloth) library to improve performance on **medical reasoning** tasks. It can be adapted for legal reasoning and other domain-specific tasks like clinical decision support or question generation.

---

## 🚀 Features

- ✅ Uses LoRA (Low-Rank Adaptation) for efficient fine-tuning
- ✅ Supports **4-bit quantization** for memory efficiency
- ✅ Trained on the [medical-o1-reasoning-SFT](https://huggingface.co/datasets/FreedomIntelligence/medical-o1-reasoning-SFT) dataset
- ✅ Includes structured medical prompts and Chain-of-Thought (CoT) reasoning
- ✅ Integrated with **Weights & Biases** and **Hugging Face Hub**

---

## 🧰 Tech Stack

- Python
- 🤗 Transformers
- 🦥 Unsloth
- 🧠 DeepSeek-R1 (Distilled LLama 8B)
- 🩺 Medical CoT Dataset
- 🧪 Weights & Biases for tracking
- 🗃️ Hugging Face Hub for model storage

---

## 📦 Installation

Install the required packages:

pip install unsloth
pip install --force-reinstall --no-cache-dir --no-deps git+https://github.com/unslothai/unsloth.git
pip install bitsandbytes triton wandb

