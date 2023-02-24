For running the python_kaplan_meier.ipynb
- set envirnment based on requirements.txt or can follow below commands to create the environment name as km-python-env and kernel name as km-python
conda create --name km-python-env 
Conda activate km-python-env 
Conda install ipykernel
python -m ipykernel install --user --name  km-python 
conda install -c conda-forge scikit-survival 
Conda install numpy
Conda install pandas
conda install -c conda-forge lifelines

- under the clinical_dashboards folder add a folder named csv and place downloaded the Synthea csv files(patient.csv, medication.csv and condition.csv) under the csv folder