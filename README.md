📘 Personal LLM Finetuning with Unsloth:
This notebook demonstrates how to fine-tune large language models (LLMs) such as LLaMA 3.1, Mistral, and others using Unsloth. 
It utilizes adapter-based fine-tuning (LoRA and QLoRA) for efficient training and includes support for multiple chat formats and datasets.


🚀 Key Features:
Supports multiple models: LLaMA, Mistral, Phi-3, Gemma, Yi, Vicuna, DeepSeek, TinyLLaMA, Open Hermes, and more.
Adapter-based training: Utilizes 16-bit LoRA or 4-bit QLoRA, reducing memory usage and training time.
Automatic RoPE scaling: Dynamically adapts max_seq_length.
Multi-turn conversation formatting: Converts datasets like FineTome-100k to HuggingFace format.
Colab and Ollama-ready: Easy deployment via Google Colab or export to Ollama.


🧠 Objective:
The goal of this notebook is to allow individuals to personalize LLMs for specific tasks. 
Such as financial budgeting, chatbot fine-tuning, or domain-specific QA systems, using efficient training methods that require fewer resources.


📁 Project Structure:
Notebook: Copy_of_Personal_Finetuning.ipynb
Dataset: Uses mlabonne/FineTome-100k (ShareGPT format)
Library: Built on top of Unsloth


🛠️ Setup:
Clone or download the repo.
Open the notebook in Colab or Jupyter.

Install dependencies:
python
Copy
Edit
!pip install --upgrade transformers
Run the notebook cells sequentially.


📊 Output:
Finetuned model adapters saved locally or uploaded to Hugging Face.
Data preprocessed into LLaMA 3.1-compatible multiturn conversations.


📦 Dependencies:
unsloth
transformers
datasets
peft (for LoRA)
Google Colab (if using drive integration)


📝 Notes:
LoRA updates only 1–10% of model weights, making it ideal for personal machines.
Can be exported directly to Ollama or used with LangChain for integration.
Both the .py and .ipynb files are the same.


👨‍💻 Author:
Elsayed Zaki
