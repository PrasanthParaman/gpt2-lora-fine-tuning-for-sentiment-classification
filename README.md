# gpt2-lora-fine-tuning-for-sentiment-classification

This project demonstrates how to fine-tune **GPT-2** using **LoRA (Low-Rank Adaptation)** for a lightweight, efficient approach to **sentiment classification** on the IMDb movie reviews dataset. Built with Hugging Face Transformers, PEFT, and PyTorch.

---

## Project Overview

-  **Task**: Binary text classification (Positive vs. Negative sentiment)
-  **Model**: GPT-2 with LoRA-injected attention & feedforward layers
-  **Fine-Tuning**: Performed using PEFT (Parameter-Efficient Fine-Tuning)
-  **Dataset**: IMDb from Hugging Face Datasets
-  **Output**: Lightweight, merged GPT-2 model ready for inference

---

## Tech Stack

- 🤗 [Transformers](https://github.com/huggingface/transformers)
- 🤗 [Datasets](https://github.com/huggingface/datasets)
-  [PEFT (LoRA)](https://github.com/huggingface/peft)
-  PyTorch

--- 

## Sample Inference Output

```text
Review: I loved this movie. It was smart, funny, and emotionally engaging...
True Label:    Positive
Predicted Label: Positive
------------------------------------------------------------
Review: The film was a disappointment. Poor acting, dull dialogue, and painfully slow pacing...
Actual Label:    Negative
Predicted Label: Negative
------------------------------------------------------------
```

---

## Directory Structure

```
.
├── LightweightFineTuning.ipynb       # Main training script
├── /tmp/gpt2-lora-imdb/            # Saved LoRA adapter (inference ready)
└── README.md
```

---

## What You Learn

- How to apply LoRA for efficient fine-tuning
- How to customize and train GPT-2 for sequence classification
- How to merge and export a PEFT model for production inference

---

## Credits

- This was part of an Udacity project

---

## License

This project is released under the MIT License.
