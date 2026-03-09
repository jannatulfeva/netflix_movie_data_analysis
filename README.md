# netflix_movie_data_analysis

Analyzing movie performance, genre trends, and audience ratings using the TMDB dataset and Python.

# Overview
This project explores a dataset of nearly 10,000 movies to identify what makes a film successful on platforms like Netflix. By analyzing popularity scores, vote counts, and genres, the project aims to uncover patterns in audience preferences and filming trends over time.

# Business Objective
The main objectives of this project are:

- Identify the most frequent and popular movie genres within the dataset.

- Track filming rates by year to determine which periods saw the highest production output.

- Analyze the relationship between popularity scores and user voting averages.

- Categorize movies into performance tiers (popular, average, etc.) to better understand market distribution.

- Highlight specific top-performing movies and their unique genre combinations.

# Dataset
The project uses the mymoviedb.csv dataset containing 9,827 movie records.

Important columns include:

- Release_Date (Initial release year)

- Title (Movie name)

- Popularity (Numeric popularity score)

- Vote_Count and Vote_Average (User rating metrics)

- Genre (Category tags)

# Tools & Technologies
The analysis was performed using:

- Python

- Pandas & NumPy 

- Matplotlib & Seaborn 

- Jupyter Notebook

# Data Cleaning & Preparation

Before performing analysis, several preprocessing steps were completed:

- Casted the Release_Date column into a datetime format and extracted the year to simplify time-based analysis.

- Dropped unnecessary columns such as Overview, Original_Language, and Poster_Url that were not required for the specific research questions.

- Handled the Genre column by splitting comma-separated values and removing white spaces to ensure categories were properly counted.

- Categorized the Vote_Average column into four distinct labels—"popular", "average", "below-avg", and "not_popular"—to facilitate easier comparison and analysis.

# Key Findings

- Genre Dominance: The Drama genre is the most frequent, appearing in more than 14% of the total dataset.

- Fan Favorites: Drama also leads in popularity, making up over 18.5% of the most highly-voted movies.

- Production Peaks: The year 2020 recorded the highest filming rate in the entire dataset.

- Top Performance: Specific titles like "The United States" were identified as having the highest popularity ratings across multiple genres.

# Visualizations

<img width="732" height="692" alt="Screenshot 2026-03-09 153249" src="https://github.com/user-attachments/assets/3e0173df-b21f-4e33-9157-5606505bdc82" />

<img width="710" height="695" alt="Screenshot 2026-03-09 153303" src="https://github.com/user-attachments/assets/c7b966fe-d768-451d-a3a1-1b5c26cd6e5f" />

<img width="773" height="598" alt="Screenshot 2026-03-09 153318" src="https://github.com/user-attachments/assets/b651dd5c-17b6-4b8f-abb9-40de3f8f2c56" />

# How to Run This Project
Clone the repository
git clone https://github.com/jannatulfeva/netflix_movie_data_analysis.git

Install required libraries
pip install pandas numpy matplotlib seaborn

Open and run the notebook
Run the notebook: netflix_movie_data_analysis.ipynb












