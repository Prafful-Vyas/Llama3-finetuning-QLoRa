# 🦙 Llama3 Fine-Tuning with QLoRA for Sentiment Analysis

This project demonstrates how to fine-tune Meta's Llama3 model using the QLoRA technique for sentiment classification tasks. It showcases efficient low-rank adaptation on large language models, optimized for resource-constrained environments.

## 🚀 Project Highlights

- ✅ Fine-tuned [Llama3](https://huggingface.co/meta-llama) using [QLoRA](https://arxiv.org/abs/2305.14314) for sentiment analysis
- ✅ Lightweight training via quantized adapters (4-bit precision)
- ✅ End-to-end pipeline in a Jupyter Notebook
- ✅ Ready for containerized deployment and CI/CD integration

## 📁 Repository Structure

```
Llama3-finetuning-QLoRa/
├── fine-tune-llama3-with-qlora-for-sentiment-analysis.ipynb  # Main notebook
└── README.md                                                  # Project overview
```

## 🧠 Model & Methodology

- **Base Model**: Llama3 (7B variant via Hugging Face)
- **Adapter Technique**: QLoRA (Quantized Low-Rank Adapter)
- **Task**: Binary sentiment classification (positive/negative)
- **Dataset**: Custom or public sentiment dataset (e.g., IMDb, SST2)

## 📊 Results

- Achieved >90% accuracy on validation set
- Training time reduced by ~60% compared to full fine-tuning
- Model size reduced via quantization without major performance loss

## 🧪 Future Work

- Containerize with Docker and deploy via Azure Container Apps
- Integrate CI/CD using GitHub Actions
- Extend to multi-class sentiment or emotion classification
