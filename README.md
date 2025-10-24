# 🌍 Neural Machine Translation (NMT) Fine-Tuning Project

### 🧠 Overview
This notebook demonstrates an end-to-end workflow for fine-tuning a Neural Machine Translation (NMT) model using the Hugging Face Transformers ecosystem.  
The goal is to build a translation system for Nigerian languages (Yoruba, Igbo, Hausa) to English, leveraging modern transfer learning and parameter-efficient techniques.

---

### ⚙️ Key Features
- Fine-tuning multilingual Seq2Seq models (e.g., `facebook/nllb-200-distilled-600M`)  
- Data preprocessing and tokenization with Datasets and Transformers  
- Efficient training with LoRA (PEFT) for reduced GPU usage  
- Model evaluation using BLEU and validation loss tracking  
- Inference section for generating translations on unseen text  

---

### 🧩 Workflow Steps
1. Environment Setup – install and configure dependencies.  
2. Load Data – import training, validation, and test datasets.  
3. Preprocess Data – tokenize and prepare text for model input.  
4. Training Setup – define parameters, metrics, and evaluation strategy.  
5. Model Training & Evaluation – fine-tune the model and assess its performance.  
6. Inference & Submission – translate unseen data and export predictions.

---

### 📊 Results
After training, the model demonstrates strong translation accuracy across all three target languages.  
Further optimization through hyperparameter tuning, larger datasets, or extended epochs can yield even better results.

---

### 💡 Future Improvements
- Explore QLoRA for lightweight fine-tuning.  
- Incorporate domain-specific datasets for cultural or technical accuracy.  
- Deploy using Gradio or FastAPI for real-time translation.

---

### 👨‍💻 Author
Emmanuel Ebiendele  
Data Scientist | Machine Learning Engineer 

📫 Connect with me:  
- 💼 [LinkedIn – Emmanuel Ebiendele](https://www.linkedin.com/in/emmanuel-ebiendele-063ba0255)  
- ⭐ [GitHub – emmanuel-123tech](https://github.com/emmanuel-123tech)  

💬 *Exploring data, AI, and innovation — one project at a time.*  
🚀 *Always open for collaboration and impactful AI research.*
