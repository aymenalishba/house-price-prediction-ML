# House Price Prediction Using Machine Learning & Deep Learning
This project predicts house prices using machine learning and deep learning models. 
It includes data preprocessing, ANN model training, explainable AI (SHAP), and 
deployment using Flask on localhost. The project is completed weekly from Week 7 
to Week 14 following DS workflow: cleaning → modeling → ANN → explainability → deployment.
project/
│── data/
│── notebook/
│   ├── model_training.ipynb
│   ├── explainability.ipynb
│── model/
│   └── model.pkl
│── app/
│   └── main.py
│── requirements.txt
│── README.md
## How to Run the Jupyter Notebook
1. Open Google Colab or Jupyter Notebook.
2. Upload the notebooks from the /notebook folder.
3. Run all cells in order:
   - Data preprocessing
   - Model training
   - ANN training (Week 9)
   - Explainability (Week 14)
4. The final model is saved as model.pkl in /model folder.
## How to Run the API (Flask)
1. Open the /app folder.
2. Install required libraries: pip install -r requirements.txt
3. Run the API: python main.py
4. Open in browser: http://localhost:5000
5. Send POST request:  POST http://localhost:5000/predict
   ## Libraries Used
- pandas
- numpy
- scikit-learn
- tensorflow / keras
- matplotlib
- seaborn
- shap
- flask
- pickle
## Explainability (SHAP)
SHAP was used to explain why the model made specific predictions.
The explainability notebook is in /notebook/explainability.ipynb.
SHAP force plots and summary plots show feature impact on prediction.


