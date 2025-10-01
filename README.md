# BBC News Classification 📰

This project classifies **BBC News articles** into categories such as **business, entertainment, politics, sport, and tech** using both **Machine Learning** and **Deep Learning** techniques.

---

## 🎯 Objective

The goal is to automatically categorize BBC news articles, providing a hands-on application of text classification in Natural Language Processing (NLP).

---

## 📂 Repository Structure

| File/Folder       | Description |
|-------------------|-------------|
| `dataset/`        | BBC News dataset (download from Kaggle) |
| `home.py` | Main code for preprocessing, training, and evaluation |
| `requirements.txt`| Dependencies (libraries needed to run the project) |
| `README.md`       | Project documentation |

---

## 📦 Requirements

To run this project, install the required packages. It is recommended to use a virtual environment:

```bash
python3 -m venv env
source env/bin/activate   # On Linux/macOS
# or on Windows: env\Scripts\activate
pip install -r requirements.txt
```
---

## 🚀 How to Run

1. Download the BBC dataset from [Kaggle](https://www.kaggle.com/datasets/shivamkushwaha/bbc-full-text-document-classification) and place it inside `dataset/`.  
2. Open and run the provided notebook or script (`home.ipynb` ).  
3. Check the outputs, visualizations, and model performance results.  

---

## 📊 Results
  
- Deep learning models (RNN, LSTM, GRU) were implemented and compared.  
- LSTM and GRU models outperformed the simple RNN.  
- Overall, GRU achieved the best accuracy on the BBC News dataset.   

---

## 👤 Author

**abdosaied22**
