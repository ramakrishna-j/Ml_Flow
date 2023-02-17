# mle-training-mlflow

**To run the file**


1) We have to create an environment from conda.yaml file which is attached in this repository .

2) First we have to download that file and save it in working directory.

3) "conda env create -f conda.yaml" Type this command in the terminal .

4) Now we can see newly created environment by typing the command "conda env list" .

5) Activate the environment -- "conda activate mlflow-env"
  
6) Use below code to launch the ML-Flow server:-
  mlflow server --backend-store-uri mlruns/ --default-artifact-root mlruns/ --host 0.0.0.0 --port 5000
  
  
**To execute the script**
  
$
conda env create -f conda.yml"

$
conda activate mlflow-env"

$
mlflow server --backend-store-uri mlruns/ --default-artifact-root mlruns/ --host 0.0.0.0 --port 5000 
