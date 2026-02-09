# Machine Learning Project

## Project Description
This project is part of the Machine Learning course and aims to train different machine learning methods to predict the credit risk of bank customers. The "Default of Credit Card Clients Dataset" available on Kaggle is used.

## Project Structure
The project contains the following files and folders:

- `Proyecto ML.ipynb`: Main notebook containing the analysis, data cleaning, model training, and metric evaluation.
- `requirements.txt`: File with the necessary dependencies to run the project.
- `dataset/UCI_Credit_Card.csv`: CSV file with the data used for analysis and training.

## Requirements
To run this project, you need:

- Python 3.8 or higher.
- The dependencies listed in `requirements.txt`.
- Jupyter Notebook or Google Colab.

## Dataset Configuration
The dataset file `UCI_Credit_Card.csv` must be located in the appropriate path depending on the execution environment:

- **Google Colab**: The file path should be `/content/UCI_Credit_Card.csv`. Make sure to upload the file to the root directory of Colab.
- **Local Execution**: The file should be located in the `dataset/` folder within the project directory.

## Installation
1. Clone this repository or download the files.
2. Install the dependencies by running the following command:

```bash
pip install -r requirements.txt
```

## Execution
1. Open the `Proyecto ML.ipynb` file in Jupyter Notebook or Google Colab.
2. Ensure the dataset file is in the correct path according to the execution environment.
3. Run the notebook cells in order to perform the analysis and train the models.

## Implemented Models
The following models were implemented in this project:

- **K-Means**: Unsupervised clustering to group customers.
- **PCA**: Dimensionality reduction using Principal Component Analysis.
- **Linear Regression, Ridge, and Lasso**: Regression models to predict the target variable.
- **K-Nearest Neighbors (KNN)**: Classification based on nearest neighbors.
- **Decision Tree**: Classification using decision trees.

## Results
- The metrics of each model were evaluated to determine their performance.
- Visual analyses and metrics such as Silhouette Score, Davies-Bouldin, RMSE, among others, were performed.

## Data Source
The data was taken from the Kaggle platform: [Default of Credit Card Clients Dataset](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset/data).

## License
This project is licensed under the GPL-3.0 License. See the `LICENSE` file for more details.

---

**Author:** Juan Miguel Blanco Medina  
**Email:** juanmblancom@gmail.com