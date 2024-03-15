
#  **CreditCardFraud Detection Project** 

 How to run the project:
1. Create a new conda environment with the following command:

```bash
conda create -p venv python==3.9.18 -y
```

2. Activate the conda environment with the following command:
```bash
conda activate venv/
```

3. Install the package requirements:
```bash
pip install -r requirements.txt
```
4. Export the following parameters

```bash
export MLFLOW_TRACKING_USERNAME=LolaPrasad
```
```bash
export MLFLOW_TRACKING_PASSWORD=b3dd566df7aa0993bd001ce80436a98f1df03907
```

5. Run the training pipeline to train the model and create the artifacts:
```bash
python src/pipelines/training_pipeline.py
```

6. Mlflow ui can be accessed by running: (Optional)
```bash
mlflow ui
```

7. Run:
```bash
streamlit run application.py ## initiates streamlit application
```

8.Upload data:
```
Upload csv file to get the results
```

#### Mlflow tracking with dagshub:

```angular2html
MLFLOW_TRACKING_URI=https://dagshub.com/LolaPrasad/credit_card_default_predictor.mlflow
```

Streamlit cloud link = https://creditcardapp.streamlit.app/#credit-card-fraud-detection

App Url =https://creditcardapp.streamlit.app/

#### Docker image
```docker
docker pull 
```


