## 🤖 AI Features of the App

### 📊 Budgeting Model (for Individuals and Businesses)
The app features an intelligent budgeting model that analyzes a user's income and expenses to generate an optimal budget. It is designed to support both individuals and businesses, enabling them to manage and allocate their resources effectively.

### 🔬 OCR Model (Receipt Scanner)
The app includes an OCR (Optical Character Recognition) feature that allows users to upload a photo of a receipt. The model automatically extracts and classifies items from the receipt, then forwards the categorized data to the budgeting model for further analysis and budget optimization.


 
# 📂 Project Contents

## 1. `generate_prompt_data.ipynb`
Generates the JSONL file necessary for supervised fine-tuning.

**Input Data:**
- `business_financial_data.csv`
- `dataset.csv`

---

## 2. `Copy_of_Personal_Finetuning.ipynb` (for individuals)  
## `financial_project.ipynb` (for businesses)
Performs the actual fine-tuning process using the generated JSONL files.

**Input Data:**
- `dataset.jsonl`
- `business_dataset.jsonl`

---

## 3. `Untitled1 (1).ipynb`
Handles OCR (Optical Character Recognition) processing.

**Input:**
- Takes a picture of any receipt




🧑‍💻 Author 
Elsayed Zaki - Hanin Daiaa - Eyad Al-Hussaini
