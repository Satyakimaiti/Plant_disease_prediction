PlantDiseasePrediction
🌿 Plant Disease Prediction App
A deep learning-based web app to predict plant diseases from leaf images for 9 major crops — Apple, Banana, Corn, Cotton, Mango, Potato, Rice, Sugarcane, and Tomato — using crop-specific trained models.

Hosted using Streamlit Community Cloud.

🚀 Features
📷 Upload plant or leaf images
🤖 Predict disease class with confidence score
💊 Get fertilizer suggestions based on disease and crop
📊 Visualize prediction probabilities (accuracy graph)
🔁 Start-over functionality for new predictions
🧠 Supported Crops and Diseases
Each crop uses a dedicated .h5 Keras model trained on labeled plant disease datasets.

✅ Supported Crops
Apple
Banana
Corn
Cotton
Mango
Potato
Rice
Sugarcane
Tomato
Each crop supports multiple diseases including healthy condition.

📁 Folder Structure
Plant_disease_prediction/ │ ├── app.py # Main Streamlit app ├── requirements.txt # Python dependencies └── models/ # Trained models for each crop ├── apple_disease_model.h5 ├── banana_disease_model.h5 ├── corn_disease_model.h5 └── ... (other crops)

yaml Copy Edit

🔧 How to Run Locally
Clone the repo:
git clone https://github.com/<your-username>/Plant_disease_prediction.git
cd Plant_disease_prediction
Create virtual environment (optional but recommended):

bash Copy Edit python -m venv venv source venv/bin/activate # On Windows: venv\Scripts\activate Install dependencies:

bash Copy Edit pip install -r requirements.txt Run the app:

bash Copy Edit streamlit run app.py 
