# data-sourcing-challenge

# Retrieve Movie Data

## Description

This project retrieves and merges movie review data from the New York Times and The Movie Database (TMDb). The merged data is cleaned and exported to a CSV file.

## Installation

1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/yourusername/your-repo.git
    ```
2. Navigate to the project directory:
    ```sh
    cd your-repo
    ```
3. Install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Add your API keys to a `.env` file:
    ```ini
    NYT_API_KEY=your_nyt_api_key
    TMDB_API_KEY=your_tmdb_api_key
    ```
2. Run the Jupyter Notebook `retrieve_movie_data.ipynb` to retrieve and merge the data.
3. The merged data will be saved as `merged_data.csv` in the project directory.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Dataset

The `merged_data.csv` file contains the following columns:

- `title`: The title of the movie.
- `headline`: The headline of the New York Times review.
- `web_url`: The URL to the New York Times review.
- `snippet`: A snippet from the New York Times review.
- `source`: The source of the review.
- `keywords`: Keywords associated with the review.
- `pub_date`: The publication date of the review.
- `byline`: The byline of the review.
- `word_count`: The word count of the review.
- `genres`: The genres of the movie.
- `spoken_languages`: The languages spoken in the movie.
- `production_countries`: The countries where the movie was produced.
- `release_date`: The release date of the movie.
- `runtime`: The runtime of the movie.
- `overview`: A brief overview of the movie.

## License

This project is licensed under the MIT License.
