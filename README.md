🐞 Bug Priority Prediction using Hybrid Deep Learning Model
This project aims to predict the priority level of software bugs by combining textual and tabular features using a hybrid deep learning model based on RNN (Recurrent Neural Network) and MLP (Multi-Layer Perceptron). The system assists developers and triagers by automatically classifying bug reports, helping teams focus on the most critical issues first.

📊 Dataset
📂 Source: Bug Priority Dataset
The dataset includes:
Issue_id
Priority (Target label)
Component, Duplicated_issue, Title, Description
Status, Resolution, Version
Created_time, Resolved_time
🧠 Model Overview
The system uses a hybrid deep learning architecture:

🔤 RNN processes unstructured data like bug Title and Description.
📊 MLP processes structured features such as Component, Version, and Timestamps.
Final prediction combines both representations to classify bug Priority.
🚀 Technologies Used
Python, Jupyter Notebook
TensorFlow / Keras
Scikit-learn, Pandas, NumPy
NLTK for NLP preprocessing
SMOTE for class balancing
TF-IDF for feature vectorization
Matplotlib / Seaborn for visualizations
📁 Repository Structure
/Bug-Priority-prediction-using-hybrid-deep-learning-model ├── project_bug_priority.ipynb # Main notebook with model code ├── software_engineering.png # Project image/logo ├── software_engeeneering_project[1].pptx # Presentation slides ├── se final report .docx # Project report document ├── A_Deep_Learning_Based_Bug_Priority_.pdf # Reference research paper 1 └── A_Dataset_of_High_Impact_Bugs_...pdf # Reference research paper 2

🧪 How to Run
Clone the repository:
git clone https://github.com/A-Charith/Bug-Priority-prediction-using-hybrid-deep-learning-model.git
📈 Output & Evaluation
Model is evaluated using metrics:
Accuracy
Precision, Recall, F1-Score
Confusion Matrix
Visualizations are provided for class distribution and model performance.
📚 Reference Papers
A Deep Learning-Based Bug Priority Prediction
A Dataset of High-Impact Bugs
