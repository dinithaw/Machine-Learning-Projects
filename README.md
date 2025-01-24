# Music Recommender System

This project is a Music Recommender System that uses a Decision Tree Classifier to predict the genre of music a user might like based on their age and gender.

## Project Structure

- `buidModel.ipynb`: Notebook to build and train the model.
- `getAccuracy.ipynb`: Notebook to evaluate the accuracy of the model.
- `loadModel.ipynb`: Notebook to load the trained model and make predictions.
- `visualizeModel.ipynb`: Notebook to visualize the decision tree model.
- `music.csv`: Dataset containing user information and their preferred music genre.
- `music-recommender.joblib`: Serialized trained model.
- `music-recommender.dot`: Visualization of the decision tree.
- `transactions.xlsx`: Placeholder for additional data (currently empty).

## Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Build the Model**:
    Open and run all cells in [buidModel.ipynb](http://_vscodecontentref_/1) to train the model and save it as [music-recommender.joblib](http://_vscodecontentref_/2).

2. **Evaluate Accuracy**:
    Open and run all cells in [getAccuracy.ipynb](http://_vscodecontentref_/3) to evaluate the accuracy of the model.

3. **Load and Predict**:
    Open and run all cells in [loadModel.ipynb](http://_vscodecontentref_/4) to load the trained model and make predictions.

4. **Visualize the Model**:
    Open and run all cells in [visualizeModel.ipynb](http://_vscodecontentref_/5) to visualize the decision tree.

## Dataset

The dataset [music.csv](http://_vscodecontentref_/6) contains the following columns:
- `age`: Age of the user.
- `gender`: Gender of the user (1 for male, 0 for female).
- `genre`: Preferred music genre of the user.

## License

This project is licensed under the MIT License. See the [LICENSE](http://_vscodecontentref_/7) file for details.

## Acknowledgements

- [Scikit-learn](https://scikit-learn.org/stable/)
- [Pandas](https://pandas.pydata.org/)
- [Joblib](https://joblib.readthedocs.io/en/latest/)