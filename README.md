# 🦙🔧 Unsloth Llama-3 LoRA Fine-Tuning — Self-Learning Project

This project demonstrates how to **fine-tune a Llama-3 model** using **Unsloth**, **LoRA** (or QLoRA), and the **`trl` library’s SFTTrainer** on a small, open instruction-following dataset.  
It’s designed as a **self-study pipeline** for understanding **parameter-efficient fine-tuning** of modern LLMs.

---

## 📌 What You’ll Learn

✅ How to:
- Load and quantize large LLMs (4-bit)  
- Apply LoRA (Low-Rank Adaptation)  
- Use instruction-style chat templates  
- Use `trl`’s **SFTTrainer** for supervised fine-tuning  
- Run inference with your fine-tuned model

---

## ⚡️ Technologies Used

- [Unsloth](https://github.com/unslothai/unsloth) — Fast PEFT for Llama-family models  
- [Hugging Face Transformers](https://huggingface.co/docs/transformers)  
- [TRL](https://github.com/huggingface/trl) — for SFT and RLHF pipelines  
- [🤗 Datasets](https://huggingface.co/docs/datasets) — load and process dataset  
- [WandB](https://wandb.ai) *(optional)* — track experiments

---

## 📂 Dataset Used

This example uses [mlabonne/FineTome-100k](https://huggingface.co/datasets/mlabonne/FineTome-100k) — a compact, diverse instruction-following dataset based on ShareGPT-like conversational pairs.

---

## 📌 Prerequisite

- You will rewuire wandb api to track logging
- Get it from - [WandB](https://wandb.ai) 

## ⚡️ Next Steps:
- Will implement PPO using trl library
- Which includes training Reward Model first



