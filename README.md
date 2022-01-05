# InternetFirewallSupervisedLearning
Predicting the Internet Firewall action based on log info. Supervised Learning Assignment for Master DSLS.

All justifications and information about the dataset can be found in ```InternetFirewallSupervisedLearning.ipynb```.


## Data availability
- [Direct link](https://archive.ics.uci.edu/ml/machine-learning-databases/00542/log2.csv)
- [Archive link with some info](https://archive.ics.uci.edu/ml/datasets/Internet+Firewall+Data)
- [F. Ertam and M. Kaya, Classification of firewall log files with multiclass support vector machine, 2018 6th International Symposium on Digital Forensic and Security (ISDFS), 2018, pp. 1-4, doi: 10.1109/ISDFS.2018.8355382.](https://doi.org/10.1109/ISDFS.2018.8355382)

## Installation Guide:
1. Install Python3
```
sudo apt-get update
sudo apt-get install python3.7
```
2. Create virtual environment
```
python3 -m venv CHOOSE/YOUR/OWN/PATH/IFSLvenv
```
3. Upgrade pip
```
CHOOSE/YOUR/OWN/PATH/IFSLvenv/bin/python3 -m pip install --upgrade pip
```
4. Activate environment
```
source CHOOSE/YOUR/OWN/PATH/IFSLvenv/bin/activate
```
6. install requirements
```
pip install -r requirements.txt
```
6. Launch jupyter notebook
```
jupyter notebook
```
