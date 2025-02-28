# LLaMA-2-CPU-Runner

## 🚀 Overview  
This project enables **LLaMA 2** to run efficiently on **CPU** without requiring an NVIDIA GPU. It uses **llama.cpp** and quantized GGUF models for optimized text generation.

## 📌 Features  
✅ Runs **LLaMA 2** without a GPU (CPU-only)  
✅ Uses **llama.cpp** for fast inference  
✅ Supports **GGUF quantized models** for low-memory usage  
✅ Works on **Google Colab & local machines**  

---

## 🔧 Installation  

### **1️⃣ Install Dependencies**  
Run the following command:  
```bash
pip install llama-cpp-python

```
Download LLaMA 2 Model (GGUF Format)
wget -O llama-2-7b.Q4_K_M.gguf https://huggingface.co/TheBloke/Llama-2-7B-GGUF/resolve/main/llama-2-7b.Q4_K_M.gguf


⚡ Performance Tips
Use smaller quantized models (e.g., Q2_K.gguf) for faster inference
Set max_tokens=512 for longer responses
Run on Google Colab with T4 GPU for better speed
