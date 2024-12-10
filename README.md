# Transformer Fine-Tuning on MRPC  

This project fine-tunes a transformer model on the **Microsoft Research Paraphrase Corpus (MRPC)** dataset. The MRPC dataset contains pairs of sentences labeled as paraphrases or non-paraphrases. The notebook uses transfer learning to adapt a pre-trained transformer model for this task.  

---

## Features  

- Load and preprocess the MRPC dataset.  
- Fine-tune a pre-trained transformer model for paraphrase detection.  
- Evaluate the model.  

---

## Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/transformer-fine-tuning-mrpc.git  
   cd transformer-fine-tuning-mrpc  
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt  
   ```

## Acknowledgments
- The MRPC dataset is provided by Microsoft Research.
- This project uses the Hugging Face transformers library for fine-tuning.
