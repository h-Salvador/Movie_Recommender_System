# Movie Recommender System

This is a movie recommender system built using Streamlit. It recommends similar movies based on the selected movie.

## Installation

1. Clone the repository:

    ```shell
    git clone https://github.com/h-Salvador/Movie_Recommender_System.git
    ```

2. Install the required dependencies:

    ```shell
    pip install -r requirements.txt
    ```

## Usage
1 Run the Movie_model.ipynb file to train the model and save the model in the Data folder.
  
2. Run the application:

    ```shell
    streamlit run app.py
    ```

3. Select a movie from the dropdown menu.

4. Click on the "Recommend" button to get a list of recommended movies.

5. The recommended movies will be displayed along with their posters.

## Data

The movie data is stored in the `Data/movies.pkl` file, which contains information about the movies such as title and ID.

## API

The application uses the [The Movie Database (TMDb) API](https://www.themoviedb.org/documentation/api) to fetch movie posters.



## License

This project is licensed under the [MIT License](LICENSE).