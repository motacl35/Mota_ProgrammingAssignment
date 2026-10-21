# Data Mining — Programming Assignment 3

This assignment contains three parts:

1. Association Rule Mining using the Apriori algorithm.
2. CNN models for Fashion-MNIST image classification.
3. BERT for multi-label emotion classification of tweets.

## Required Files

The repository includes the Jupyter notebook, grocery dataset, and tweet datasets.

The Fashion-MNIST training CSV is not included because it exceeds GitHub's 100 MB file size limit.

Download it from:

https://www.kaggle.com/datasets/zalando-research/fashionmnist

Place `fashion-mnist_train.csv` inside a folder named `Fashion-MINIST`.

## Folder Structure

```text
ProgrammingAssignment3/
├── Mota_ProgrammingAssignment3.ipynb
├── README.md
├── RU_F22_DM1_Item_Datasets/
│   └── Grocery_Items_0.csv
├── Fashion-MINIST/
│   └── fashion-mnist_train.csv (download separately)
└── student_6/
    ├── train.json
    ├── validation.json
    └── test.json
```

## Running the Notebook

1. Download or clone the repository and switch to the `ProgrammingAssignment3` branch.
2. Download the Fashion-MNIST training CSV and place it in the folder shown above.
3. Open `Mota_ProgrammingAssignment3.ipynb` in Jupyter Notebook or JupyterLab.
4. Update the `BASE` variable near the beginning of the notebook to point to your local `ProgrammingAssignment3` folder.

For example:

```python
from pathlib import Path
BASE = Path.cwd()
```

This example works when Jupyter's current working directory is the `ProgrammingAssignment3` folder.

5. Install the required Python libraries if they are not already installed, then run the notebook cells in order.

An internet connection is needed to download the pretrained BERT model the first time it runs.
