### Project Description: Book Genre Classification

This project focuses on predicting the genre of books based on their summaries using machine learning. It employs advanced preprocessing, classification techniques, and a user-friendly interface for practical usability.

#### Key Features:
1. **Dataset**:  
   The dataset (`books_data.csv`) contains book summaries and their respective genres.

2. **Preprocessing**:  
   - Text summaries are converted into numerical features using `TfidfVectorizer`.  
   - Genres are encoded using `LabelEncoder` to handle categorical labels.  
   - The dataset is balanced using **SMOTE (Synthetic Minority Oversampling Technique)** to address class imbalance.

3. **Model Training**:  
   - A **Random Forest Classifier** is utilized for genre prediction.  
   - Hyperparameters like `n_estimators=100` and `class_weight='balanced'` are configured for optimal results.

4. **Evaluation**:  
   The model's performance is evaluated using a classification report, including precision, recall, and F1-score.

5. **Deployment**:  
   - The trained model, vectorizer, and encoder are saved in `book_genre_classifier.pkl` for reuse.  
   - A Python script (`Testing and Deployment.py`) ensures smooth deployment and testing of the model.

6. **GUI Integration**:  
   A graphical user interface is built using `tkinter` to provide a user-friendly way to input book summaries and view predicted genres.

#### Additional Resources:
- **Reports**: The project includes a comprehensive AI report summarizing the methodology and findings (`report ai format.docx`).
- **Notebooks**: Jupyter notebooks (`aiproject.ipynb` and `projrct.ipynb`) detail the preprocessing, training, and evaluation steps.

This project is a comprehensive solution for automated book genre classification, leveraging machine learning techniques for practical applications in publishing and library management.
