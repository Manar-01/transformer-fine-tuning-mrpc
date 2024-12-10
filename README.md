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
## How to Run
1. Open the notebook:
``` bash
jupyter notebook qa_rag_climate_fever.ipynb
```
or use google colab 

2. Ensure the runtime is set to GPU or TPU for faster training.

3. Follow the steps in the notebook to:
   - Load and preprocess the MRPC dataset.
   - Fine-tune the transformer model.
   - Evaluate and analyze the model's performance

## Dependencies
- transformers  
- datasets  
 - tensorflow 
- numpy  
- pandas  

Install them using the requirements.txt file.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- The MRPC dataset is provided by Microsoft Research.
- This project uses the Hugging Face transformers library for fine-tuning.
