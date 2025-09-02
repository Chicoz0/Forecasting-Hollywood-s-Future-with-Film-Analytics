# The Next Big Thing: Forecasting Hollywood's Future with Film Analytics

This project focuses on analyzing IMDb film data to predict box office success. The methodology used is CRISP-DM (Cross-Industry Standard Process for Data Mining), which guides the process from business understanding to modeling and the delivery of results.

The main objective is to identify the factors that most influence a film's revenue, providing valuable insights for the film industry.

## Project Structure

The repository is organized as follows:

  - `desafio_indicium_imdb.csv`: The original dataset used for the analysis.
  - `LH_CD_FRANCISCO_DE_PAULA_LEMOS.ipynb`: The Jupyter notebook containing the full analysis, from Exploratory Data Analysis (EDA) to predictive modeling.
  - `requirements.txt`: A list of all Python libraries needed to run the project.
  - `README.md`: This file, with information about the project.
  - `imdb_rating_regressor.pkl`: The serialized machine learning model, ready to be used for revenue predictions.
  - `best_genre_model.pkl`: Another serialized machine learning model to try to predict the a genre by the film synopsis.

## How to Run the Project

Follow the steps below to install the dependencies and run the analysis:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Chicoz0/Forecasting-Hollywood-s-Future-with-Film-Analytics.git
    cd Forecasting-Hollywood-s-Future-with-Film-Analytics
    ```
2.  **Create and activate a virtual environment (recommended):**
    ```bash
    python -m venv venv
    # On Windows
    venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Run the notebook:**
    Start Jupyter Notebook or JupyterLab in the project's root directory:
    ```bash
    jupyter notebook
    ```
    Or
    ```bash
    jupyter lab
    ```
    Open the `LH_CD_FRANCISCO_DE_PAULA_LEMOS.ipynb` file and execute the cells to replicate the analysis.

## Results and Conclusions

The detailed analysis and modeling in the notebook revealed that factors such as film genre, number of votes, and the historical success of the director and actors are strong indicators of high revenue. The developed predictive model is capable of predicting a film's IMDB score based on these and other variables.

For more details on the statistical analyses, Exploratory Data Analysis (EDA), and model performance, see the `LH_CD_FRANCISCO_DE_PAULA_LEMOS.ipynb` notebook.
