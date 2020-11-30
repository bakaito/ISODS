## Files
The repo includes the following:
- **xgb_model.pckl** :XGboost model for classifying satisfactory and unsatisfactory chatbot-customer conversations
- **ISODS_train.ipynb**:Code for model training
- **ISODS_test.ipynb**:Code to load the model and predict on test data
- **vietnamese-stopwords.txt**: Text file containing list of Vietnamese stop words

All the files are required to be in the same folder along with [training and test csv files] [https://www.scriptedin.com/contests/view/47]

## Libraries
- pandas (v1.1.3)
- numpy (v1.19.2)
- regex (v2.2.1)
- scikit-learn (v0.23.2)
- [pyvi](https://pypi.org/project/pyvi/) (v)

## Usage
If using a jupyter notebook, it is convenient to create a separate conda environment and activating it prior installing these packages.

```bash
conda create --name <env_name>
```

```bash
conda activate <env_name>
```

Use the conda manager to install the packages (except pyvi, which is installed through pip)
