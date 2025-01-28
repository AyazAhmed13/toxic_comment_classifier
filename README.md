
# **Toxic Comment Classification Using Bidirectional LSTM**

## **Overview**
This project involves building a deep learning model to classify comments into multiple toxicity categories: `toxic`, `obscene`, `threat`, `insult`, `identity_hate`, and `severe_toxic`. Using a **Bidirectional LSTM** architecture, the model processes text sequences to identify toxic behaviors. A **Gradio-based web interface** is implemented to allow real-time testing and predictions.

---

## **Features**
- **Multi-Label Classification**: Simultaneously predicts multiple toxicity categories for each comment.
- **Deep Learning Model**: Leverages **Bidirectional LSTM** to analyze and capture contextual relationships in text.
- **Efficient Preprocessing**: Utilizes **TextVectorization** for tokenization and sequence padding.
- **Interactive Web Interface**: Built with **Gradio** for real-time user interaction.

---

## **Tech Stack**
- **Languages**: Python
- **Libraries/Frameworks**:
  - TensorFlow, Keras
  - Pandas, NumPy
  - Gradio, Matplotlib
- **Tools**: TextVectorization, sequence padding
- **Deployment**: Gradio web app
---

## **Model Architecture**
The model includes:
- **Embedding Layer**: Converts words into dense vector representations.
- **Bidirectional LSTM**: Processes sequences in both forward and backward directions to capture context.
- **Dense Layers**: Extracts features and performs classification.
- **Sigmoid Output Layer**: Outputs probabilities for each toxicity category.

---

## **Project Workflow**
1. **Data Preprocessing**:
   - Tokenized text using TensorFlow's **TextVectorization**.
   - Applied sequence padding to ensure consistent input size.
2. **Model Training**:
   - Trained a **Bidirectional LSTM** model with dropout layers to avoid overfitting.
   - Used **binary cross-entropy loss** and the **Adam optimizer**.
3. **Evaluation**:
   - Assessed model performance using metrics like Precision and Recall.
4. **Deployment**:
   - Built an interactive interface using **Gradio** for real-time predictions.

---

## **Future Work**
- Extend support for multilingual toxicity detection.
- Experiment with advanced models like **BERT** for improved contextual understanding.
- Optimize the Gradio interface for scalability and usability.

---

## **Contributing**
Contributions are welcome! Feel free to fork the repository and submit a pull request for improvements or suggestions.



## **Screenshots**
![Screenshot_27-1-2025_151631_](https://github.com/user-attachments/assets/4849f652-341e-42af-b171-c2f7c6cb3437)
![Screenshot_27-1-2025_151657_](https://github.com/user-attachments/assets/6a2106bf-2fd2-42d3-aaa8-aa61987fd8af)
![Screenshot_27-1-2025_151526_](https://github.com/user-attachments/assets/907e86c2-1531-4a73-8f4a-2328035ee56f)
![Screenshot_27-1-2025_151545_](https://github.com/user-attachments/assets/ec79995b-8030-4400-b785-d1ac9ea8a84e)
![Screenshot_27-1-2025_15161_](https://github.com/user-attachments/assets/f8d88753-a5a5-4f8f-939f-6d2fbec3912d)
![Screenshot_27-1-2025_151617_](https://github.com/user-attachments/assets/beeb4b1c-6c6e-4bd5-909d-229b426dd5a6)

