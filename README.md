# 🤖 Transformers Demo Pipelines

This repository contains a Colab-based demo notebook showcasing **Hugging Face Transformers pipelines** for a variety of NLP and vision tasks. It demonstrates how to use pre-trained models for text, images, audio, and even music generation.

---

## 📌 Features Implemented

### 1. **Text Classification**

* Sentiment analysis with `tabularisai/multilingual-sentiment-analysis`.

### 2. **Named Entity Recognition (NER)**

* Entity detection with `dslim/bert-base-NER`.

### 3. **Question Answering**

* Extractive QA using Hugging Face default models.

### 4. **Summarization**

* Abstractive text summarization with `Falconsai/text_summarization`.

### 5. **Translation**

* English → Hindi translation with `Helsinki-NLP/opus-mt-en-hi`.

### 6. **Text Generation**

* GPT-2 large (`gpt2-large`) for generating customer-service style responses.

### 7. **Image Classification**

* Classify images with `microsoft/swinv2-tiny-patch4-window16-256`.

### 8. **Image Segmentation**

* Semantic segmentation with `mattmdjaga/segformer_b2_clothes`.

### 9. **Text-to-Speech (TTS)**

* Convert text into speech with Hugging Face pipeline (`text-to-speech`).

### 10. **Text-to-Music**

* Generate music from text prompts using `facebook/musicgen-small`.

---

## 🚀 Getting Started

### Install Dependencies

```bash
pip install -U transformers
pip install -U sentencepiece
pip install -U sacremoses
pip install soundfile scipy
```

### Run the Notebook

* Open the notebook in Google Colab or Jupyter.
* Execute each cell step by step.

---

## 📂 Project Structure

```
├── Hello_Transformers.ipynb   # Main notebook
├── README.md                  # Project documentation
├── music.wav                  # Example music output
├── speech.wav                 # Example speech output
```

---

## 🎯 Example Use Cases

* Learn Hugging Face pipelines quickly.
* Run NLP + Vision tasks without training models.
* Experiment with multimodal AI (text, vision, audio).

---

## 🙌 Acknowledgements

* [Hugging Face Transformers](https://huggingface.co/transformers/)
* [Google Colab](https://colab.research.google.com/)
* Model authors and contributors

---

## 📜 License

This project is for **educational/demo purposes**. Check each model's license before production use.
