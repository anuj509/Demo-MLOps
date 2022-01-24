This is Demo Project for MLOps Implementation for On-prem. It uses all the open source platforms like git, DVC, MLFlow etc.


To run the training pipeline:
dvc repro

mlflow server command -
mlflow server --backend-store-uri sqlite:///mlflow.db --default-artifact-root ./artifacts --host 127.0.0.1 -p 1234


conda create --name mlops_on_prem python==3.9
conda activate mlops_on_prem
pip install -r requirements.txt 
<<<<<<< HEAD
pip install mlflow
Install dvc from this link : https://dvc.org/
=======
pip install mlflow . ...

>>>>>>> 8810e67e259757109d644df9a5b3d48c9fd1c9a9
