# DNA Splice Site Classification Using Convolutional Neural Networks (CNN)

## Project Overview

This project focuses on the classification of DNA splice site sequences using a Convolutional Neural Network (CNN). DNA splice site classification is an important problem in bioinformatics because splice sites determine how genes are processed into functional proteins. The proposed deep learning model automatically learns sequence patterns from DNA data and predicts the correct splice site category with high accuracy.

---

## Problem Statement

Identifying DNA splice sites manually is a challenging and time-consuming process due to the complexity of genomic sequences. Machine learning and deep learning techniques provide an efficient solution by automatically recognizing hidden patterns in DNA sequences. This project applies a CNN model to improve the accuracy of DNA splice site classification.

---

## Objectives

* Develop a Convolutional Neural Network (CNN) for DNA splice site classification.
* Preprocess and encode DNA sequence data for deep learning.
* Train and evaluate the CNN model using appropriate performance metrics.
* Analyze the model's performance using visualization and evaluation techniques.
* Demonstrate the application of deep learning in bioinformatics.

---

## Dataset

The project uses the DNA Splice Site dataset containing DNA sequence samples categorized into different splice site classes. The dataset was preprocessed before training the CNN model.

**Dataset Information**

* **Dataset:** DNA Splice Site Dataset
* **Data Type:** DNA Sequences
* **Target Classes:** EI (Exon-Intron), IE (Intron-Exon), and N (Neither)
* **Domain:** Bioinformatics

---

## Technologies Used

* Python
* Jupyter Notebook
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## Project Workflow

1. Import required libraries.
2. Load the DNA splice site dataset.
3. Perform data preprocessing and cleaning.
4. Encode DNA sequences into numerical representations.
5. Split the dataset into training and testing sets.
6. Build the Convolutional Neural Network (CNN).
7. Train the CNN model.
8. Evaluate the model using test data.
9. Generate the classification report and confusion matrix.
10. Visualize training accuracy and loss.
11. Draw conclusions based on the model's performance.

---

## CNN Model

The CNN model was designed to automatically extract meaningful features from encoded DNA sequences. The network consists of convolutional layers for feature extraction, pooling layers for dimensionality reduction, dense layers for classification, and a final output layer for predicting the splice site class.

---

## Model Evaluation

The trained model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report
* Confusion Matrix
* Training Accuracy
* Validation Accuracy
* Training Loss
* Validation Loss

---

## Project Structure

```text
DNA-Splice-Site-Classification-CNN/
│── splice_dna.ipynb
│── requirements.txt
│── README.md
│── data/
│── splice_dna_cnn_model.keras
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/vijetaalavani32-oss/DNA-Splice-Site-Classification-CNN.git
```

Navigate to the project folder:

```bash
cd DNA-Splice-Site-Classification-CNN
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run all cells to reproduce the results.

---

## Results

The CNN model successfully classified DNA splice site sequences by learning complex sequence patterns from the dataset. Performance was assessed using accuracy, precision, recall, F1-score, classification report, confusion matrix, and training history plots. The results demonstrate the effectiveness of Convolutional Neural Networks for DNA sequence classification tasks in bioinformatics.

---

## Future Work

* Improve model performance through hyperparameter tuning.
* Compare CNN with LSTM, GRU, and Transformer-based models.
* Train the model on larger genomic datasets.
* Deploy the model as a web application using Streamlit or Flask.
* Explore advanced sequence embedding techniques for enhanced prediction accuracy.

---

## Conclusion

This project demonstrates the application of deep learning to DNA splice site classification using a Convolutional Neural Network. The model effectively learned sequence patterns from DNA data and achieved reliable classification performance. The study highlights the potential of CNNs as powerful tools for solving complex bioinformatics problems and provides a foundation for future research in genomic sequence analysis.

---

## Author

**Vijeta Alavani**

M.Sc. Data Science

Alliance University, Bengaluru

---

## License

This project is intended for educational and academic purposes.
