🤖 AI Features of the App:

📊 Budgeting Model (for Individuals and Businesses):
The app includes an intelligent budgeting model that accepts a user's income and expenses and generates an optimal budget. 
It is tailored to work for both individuals and businesses, helping them utilize their resources effectively.

🔬 OCR Model (Receipt Scanner):
The app has a OCR feature (Optical Character Recognition) that allows users to upload a photo of a receipt. 
A model classifies the items on the receipt and passes the categorized data to the budgeting model for further processing and budget optimization.

 
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
