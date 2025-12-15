# studentlife-passive-sensing-longitudinal-study

DATA

The StudentLife dataset is:  time period/purpose, publicly available, anonymized, Dartmouth
link: https://studentlife.cs.dartmouth.edu/datasets.html
Why did I choose this dataset?
To include:  how to request the data, where to save raw data, how to unpack raw data with preprocessing script, and then EDA will be done in data/processed/

You will download a compressed file called dataset.tar.bz2
1. When you're in studentlife-passive-sensing-longitudinal/ go to terminal (bash) and type:

mv ~/Downloads/dataset.tar.bz2 data/raw 

2. Decompress this compressed file by running the following:

cd data/raw
tar -xvjf dataset.tar.bz2

3. You should see data/raw/ populated with /dataset/(many), /rawaccfeat, dataset.tar.bz2

# create and activate virtual environment
python3 -m venv .venv
source .venv/bin/activate
pip install (list of packages)
python -m ipykernel install --user --name studentlife --display-name "Python (studentlife)"

