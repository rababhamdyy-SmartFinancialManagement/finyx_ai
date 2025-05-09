🧾 Receipt Processing:
This file demonstrates how to process a receipt image using OCR and extract relevant text, which is then passed to a Mistral language model for classification, analysis, or budget-related tasks. The notebook is written with both Arabic and English annotations.


📌 Features
~ Upload and process receipt images using OCR.
~ Load and run a Mistral model (Q4_0 quantized version) from Hugging Face.
~ Apply language model inference on the extracted text to interpret or classify receipt data.
~ Fully executable within a Jupyter Notebook or Google Colab environment.


🧠 Objective
This notebook aims to automate the process of reading receipts and performing intelligent operations (e.g., expense categorization, budget advice) 
using a fine-tuned language model.


📁 Steps in the Notebook
1. Install Required Packages
2. Download and Load Mistral Model
3. Upload Receipt Image
4. Perform OCR on the Image
5. Run the Mistral Model on Extracted Text


🛠️ Setup Instructions
1. Clone or download this repository.
2. Open the Untitled1.ipynb notebook in Jupyter or Google Colab. 
3. Run the cells in order.
4. Upload a receipt image when prompted.


📦 Dependencies
transformers
torch
Pillow
easyocr or pytesseract (depending on the OCR used)
huggingface_hub


🧾 Input and Output
Input: An image of a receipt.
Output: Extracted text + language model interpretation.


🧑‍💻 Author 
Hanin Daiaa - Eyad Al-Hussaini
