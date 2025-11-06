## FINAL `README.md` 

```markdown
# 🗑️ Week 2 - Waste Classification using CNN

## Project Description
This project uses a Convolutional Neural Network (CNN) to classify waste images into 10 different categories such as paper, plastic, metal, glass, trash, etc.  
It is developed as part of the **Week 2 Milestone Project** for the AI & Data Science Virtual Internship.

---

## Repository Contents
```

week2/
├── model.ipynb          # Jupyter Notebook (training + evaluation)
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation

```

---

## 📊 Dataset
The dataset is too large to upload directly to GitHub (25MB file limit).  
You can download it from Google Drive:

🔗 **Dataset Link:**  
https://drive.google.com/drive/folders/1z1RqDCJqJKV7gwgizsiVNvrKkwb589F2?usp=sharing

After downloading, extract it like:

```

dataset/
├── battery
├── biological
├── cardboard
├── clothes
├── green-glass
├── metal
├── paper
├── plastic
├── trash

````

---

##  Model Summary
| Property | Value |
|----------|--------|
| Framework | TensorFlow / Keras |
| Model Type | Sequential CNN |
| Classes | 10 |
| Loss Function | Categorical Crossentropy |
| Optimizer | Adam |
| Input Size | 224x224 (can be modified) |
| Final Accuracy | (Update after training) |

---

## 🔧 Installation

Install dependencies using:

```bash
pip install -r requirements.txt
````

---

##  How to Run

1. Download dataset from the link above
2. Extract it into a folder named `dataset/`
3. Open `model.ipynb` in Jupyter Notebook / Google Colab
4. Run all cells to:
    Load dataset
    Train CNN model
    Evaluate model accuracy

---

##  Improvements Done by Me (as required by Week 2 task)

 Data augmentation applied
 Used train-test split for fair evaluation
 Added dropout to reduce overfitting
 Used Google Drive dataset link due to GitHub upload limit
 Organized project into clean folder structure

---

## Output Example

(Add screenshot later)

Example:

```
Test Accuracy = 91.42%
Input: plastic bottle → Output: Plastic 
```

---

##  Author

**Srinagapriya**
AI & Data Science Virtual Internship – Week 2 Submission
Edunet Foundation | IBM SkillsBuild

```

