# Book Recommender System
This project is a book recommender system implemented in a Jupyter Notebook. Using a content-based filtering machine learning algorithm, it takes user preferences and provides personalized book recommendations. Additionally, it includes various data visualizations to provide insights into the dataset.
## Features
1. Personalized Recommendations
* Uses a content-based filtering algorithm to recommend 10 books based on user preferences, including:
  * Favorite book
  * Favorite author
  * Preferred published year
  * Favorite genre
  * Book ratings preference
  * Preferred book length
* Recommendations are displayed in a table for easy review.
2. Visualizations
* Bar Graph: Average book ratings over 9 across different years.
* Pie Chart: Distribution of books across various genres.
* Line Graph: Number of pages published per year.
* Table: Summarizes the top 10 book recommendations.
3. Dataset Integration
* Converts data from a database into a pandas DataFrame for preprocessing and analysis.
## Dependencies
To run this project, ensure you have the following Python libraries installed:
* scikit-learn: For feature extraction and similarity calculations.
  * CountVectorizer
  * cosine_distances
* NLTK: For tokenization of textual data.
  * word_tokenize
* IPython: To display HTML tables in the notebook.
  * IPython.display.display
  * IPython.display.HTML
* Matplotlib: For creating static, interactive, and animated visualizations.
  * matplotlib.pyplot
* Seaborn: For enhanced data visualization.
* Pandas: For data manipulation and analysis.
  * pandas.DataFrame

Install the required libraries using the following command:
* pip install scikit-learn nltk matplotlib seaborn pandas
## How It Works
1. Preprocessing
* Loads the dataset into a pandas DataFrame.
* Tokenizes textual data for feature extraction.
* Encodes user preferences and dataset features using CountVectorizer.
2. Machine Learning Algorithm
* Calculates cosine similarity between the user’s input and the dataset.
* Identifies the top 10 most similar books based on user preferences.
## Recommendations
* Generates a table of recommendations with the book title, author, genre, and average rating.
## Visualizations
* Bar Graph: Displays books with average ratings over 9 across years.
* Pie Chart: Shows the distribution of genres in the dataset.
* Line Graph: Plots the number of pages published per year.
## How to Run
1. Clone the repository or download the Jupyter Notebook file.
2. Ensure you have installed all dependencies listed above.
3. Open the notebook in Jupyter and run all cells in the order they are listed. 
4. Input your preferences when prompted.
5. View your personalized book recommendations and explore the visualizations.
