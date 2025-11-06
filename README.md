# Week 2 - Waste Classification using CNN

##  Project Description  
This project implements a **Convolutional Neural Network (CNN)** to classify images of waste into **10 categories** such as plastic, paper, metal, glass, trash, and more.  
It is developed as part of the **Week 2 Milestone Project** of the **AI & Data Science Virtual Internship** offered by *Edunet Foundation* in collaboration with *IBM SkillsBuild*.

---

##  Repository Structure

```

week2/
├── model.ipynb          # Jupyter Notebook (training + evaluation)
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation

```

---

##  Dataset  
The dataset is too large to upload directly to GitHub (25MB file limit).  
You can download it from Google Drive:

 **Dataset Link:**  
https://drive.google.com/drive/folders/1z1RqDCJqJKV7gwgizsiVNvrKkwb589F2?usp=sharing  

Once downloaded, extract it like:

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

## Model Summary

| Property         | Value                    |
|------------------|--------------------------|
| Framework        | TensorFlow / Keras       |
| Model Type       | Sequential CNN           |
| Classes          | 10                       |
| Loss Function    | Categorical Crossentropy |
| Optimizer        | Adam                     |
| Input Size       | 224x224                  |
| Final Accuracy   | *To be updated after training* |

---

##  Installation

Install all dependencies using:

```bash
pip install -r requirements.txt
````

---

##  How to Run

1. Download the dataset from the link above.
2. Extract it into a folder named `dataset/`.
3. Open the `model.ipynb` notebook in Jupyter Notebook or Google Colab.
4. Run all cells to:

   * ✅ Load the dataset
   * ✅ Train the CNN model
   * ✅ Evaluate model accuracy

---

##  Improvements Done (as per Week 2 Task)

* ✅ Applied data augmentation
* ✅ Used train-test split for fair model evaluation
* ✅ Introduced dropout layers to reduce overfitting
* ✅ Hosted dataset externally due to GitHub file size limits
* ✅ Clean and organized project structure

---

## 📸 Output Example

*(Add screenshot later)*

Example:

```
Test Accuracy = 91.42%

Input: plastic bottle  
Predicted Output: Plastic
```

---

##  Author

**Srinagapriya**
AI & Data Science Virtual Internship – Week 2 Submission
Edunet Foundation | IBM SkillsBuild

```

---

Let me know if you want me to personalize it further or generate a PDF version of this README!
```
