# Spam-Detection-Using-LSTM

#  Spam Detection System Using LSTM Deep Learning Model

##  Project Overview

This project is a Deep Learning-based Spam Detection System that classifies SMS messages as **Spam** or **Not Spam (Ham)** using an LSTM (Long Short-Term Memory) Neural Network.  

The system applies Natural Language Processing (NLP) techniques such as tokenization and padding to preprocess text data and train the model for accurate spam message prediction.

---

#  Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Hugging Face Datasets
- Matplotlib

---

#  Dataset

The project uses the **SMS Spam Dataset** loaded directly using the Hugging Face `datasets` library.

Dataset Categories:
- **Spam**
- **Ham (Normal Messages)**

---

#  Project Workflow

```text
Load Dataset
      ↓
Text Preprocessing
      ↓
Tokenization
      ↓
Padding
      ↓
LSTM Model Training
      ↓
Evaluation
      ↓
Prediction
```

---

#  Model Architecture

- Embedding Layer
- LSTM Layer
- Dropout Layer
- Dense Output Layer

---

#  Results

Achieved approximately **98% accuracy**  

Successfully classifies spam and non-spam messages  

Performs accurate prediction on new SMS messages

---

#  Sample Prediction

```python
Input Message:
"Congratulations! You won a free prize"

Prediction:
Spam Message
```

---

#  Conclusion

This project demonstrates the practical implementation of Deep Learning and NLP techniques for intelligent spam message classification using an LSTM Neural Network.

---

#  Author

**Hania Eman**
