# Predicting Legal U.S. Tender Using Machine Learning
This program was created and run in Jupyter Notebook version 7.2.2. It applies various machine learning classifiers to predict whether a coin is legal U.S. tender based on a self-created dataset. The dataset includes various physical properties of coins, and multiple models were trained and evaluated to determine the best-performing classifier.

## Installation
Install Anaconda Navigator: 

Download and install [Anaconda Navigator](https://www.anaconda.com/products/navigator) (which includes both Python and Jupyter Notebook) if you haven't already.

Clone the repository:

Open "anaconda_prompt" through Anaconda Navigator, and navigate to the folder where you want to store the project. Then, clone the repository using Git:

```bash
gh repo clone gengelde/predicting-legal-tender
```
Install dependencies:

Install the required libraries using the following:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage
Open [Anaconda Navigator](https://www.anaconda.com/products/navigator):

Launch [Anaconda Navigator](https://www.anaconda.com/products/navigator) from your start menu or applications folder.

Navigate to the project directory:

Once [Anaconda Navigator](https://www.anaconda.com/products/navigator) is open launch Jupyter Notebook by clicking the "Launch" button under Jupyter Notebook.

Open the Notebook:

In the Jupyter Notebook interface that opens in your web browser, navigate to the predicting-legal-tender directory (where you cloned the repository) and locate the Coin_Dataset_Prediction_Engelder.ipynb file.

Access the dataset:

The dataset coin_dataset.csv is included in the repository. You can access it directly within the notebook since it is in the same directory as the notebook. The notebook will automatically load the dataset using the file path 'coin_dataset.csv'.

Run the notebook:

Open the notebook and run each cell in sequence. This will preprocess the data, train the models, and evaluate their performance.

## Contributing

If you’d like to contribute, feel free to submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Contact

For any questions, reach out to [garrett.engelder@gmail.com](mailto:garrett.engelder@gmail.com)