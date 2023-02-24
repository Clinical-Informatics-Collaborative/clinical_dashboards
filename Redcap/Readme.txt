For running the redcap_import.ipynb
- set envirnment based on requirements.txt or can follow below commands to create the environment name as redcap-import-env and kernel name as redcap-import
conda create --name redcap-import-env 
Conda activate redcap-import-env 
Conda install ipykernel
python -m ipykernel install --user --name  redcap-import
Conda install numpy
Conda install pandas
Conda install requests

- under the clinical_dashboards folder add a folder named csv and place downloaded the Synthea csv files(patient.csv, medication.csv and condition.csv) under the csv folder