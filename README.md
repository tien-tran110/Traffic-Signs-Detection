## Traffic Sign Recognition Model using CNN
### Running locally

1. Download the Dataset from Kaggle
   Link: https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign
   Extract the downloaded dataset and place it in the appropriate directory (e.g., /Dataset). Put it in the same directory where you would clone the GitHub Repo.
2. Set Up a Python Virtual Environment
   - Navigate to the project directory: cd /path/to/your/project
   - Create a virtual environment: python3 -m venv venv
   - Activate the virtual environment:
     **Linux/Mac:** source venv/bin/activate
     **Windows:** .\venv\Scripts\activate
   - Install the required dependencies: pip install -r requirements.txt
3. Run the Final.ipynb Notebook with your favorite environment
   - This will generate a model with extension .keras file for the application afterward.
4. Run the Streamlit App
   - Navigate to the directory where app.py located
   - Run the streamlit app using: streamlit run app.py
  
#### Project Structure
```
/Traffic-Signs-Detection
│
├── app.py                            # Streamlit app file
├── requirements.txt                  # List of project dependencies
├── Dataset/                          # Directory for dataset (downloaded from Kaggle)
├── Final.ipynb                       # Notebook 
├── README.md                         # This file
└── traffic_sign_model.keras          # Directory containing trained models
```




