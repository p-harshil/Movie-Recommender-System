# Movie-Recommender-System
### Overview:
The system recommends movies to the user based on their selection (previously watched movies). The system analyzes the movie ratings, compares similarites between the 
movies user have watched and other movies from the dataset to recommend the movie that a user might enjoy based on their previous selection.

### About the Dataset:
The dataset has two data files. The files are csv formatted.
- First data file has columns ['user_id', 'item_id', 'rating', 'timestamp']
- Second data file is Movies_Title with columns ['item_id', 'title']</br>
Both the data files are merged to create a single dataframe for further analysis and training the model. Visualisation is carried out to understand the ditribution of 
ratings in the data.

### Dependecies:
- pandas
- matplotlib
- seaborn

### Future Work:
- Allowing user to select the movies they watched to recommend them movies to watch based on their taste.
- Gather more data like movie genres, user reviews to incorporate natural language processing methods for improved accuracy of recommendations.

### Instructions:
To run this project, the required libraries must be installed.
