# 📊 Product Price Prediction  
### LLM-Based Product Price Prediction using Qwen & QLoRA

PriceSense AI is a **Large Language Model (LLM)–based pricing system** that predicts the **market price of consumer products** directly from their **textual descriptions**.  
The project uses **Qwen2.5-3B**, optimized with **4-bit QLoRA quantization**, making it efficient enough to run on **Google Colab GPUs**.

---

## 🚀 Project Overview

Traditional pricing models rely heavily on structured features such as brand, category, or historical sales data.  
This project demonstrates how **modern LLMs can infer product value from natural language alone**.

> 🧠 *Given a product description, the model predicts its realistic selling price.*

---

## 🧩 Key Features

- 🔹 Predicts **numeric product prices** from text descriptions
- 🔹 Uses **Qwen2.5-3B**, an open-source large language model
- 🔹 Optimized with **QLoRA (4-bit NF4 quantization)**
- 🔹 Runs efficiently on **low-memory GPUs (~2GB VRAM)**
- 🔹 Clean evaluation pipeline using a custom `evaluate()` function

---

## 🛠️ Tech Stack

- **Model**: Qwen2.5-3B  
- **Fine-tuning**: QLoRA (PEFT)  
- **Quantization**: bitsandbytes (NF4, 4-bit)  
- **Libraries & Frameworks**:
  - `transformers`
  - `datasets`
  - `peft`
  - `accelerate`
- **Platform**: Google Colab (GPU)

