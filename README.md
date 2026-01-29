# RB-BGWDE for Early Alzheimer's Disease

This repository provides a practical implementation of the proposed RB-BGWDE framework 
for early Alzheimer's disease classification.

The pipeline includes:
- Boruta-based feature filtering
- Binary GWO-DE wrapper feature selection
- SMOTE for class balancing
- Ensemble learning 

Note:
This implementation represents a practical and reproducible version of the proposed method. 
Certain components are implemented in simplified form for computational efficiency and reproducibility.

## Dataset
The dataset used in this study is publicly available on Kaggle:
Alzheimer's Disease Dataset by Rabie El Kharoua.
https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset

## How to run
```bash
pip install -r requirements.txt
python main.py
