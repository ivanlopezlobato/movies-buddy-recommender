Unsupervised machine learning (clustering), explore the user-based collaborative filtering. 

### Intro
With streaming taking over and making movie consumption more individualistic, 
going to the cinema is more a social event, empowered by a shared experience (in the "right" or "wrong" direction).
Beyond discovering new titles and keep engaged, the idea is to find compatible people to enjoy together "Dating for movies"

### Goal
Function that get the "perfect" companion (the 2 people closest each other) after calculate the distance (sklearn Nearest Neighbor, metric= euclidean)

### Data
Trained with MovieLens dataset
https://grouplens.org/datasets/movielens/

For presentation, data collected through Survey
https://forms.gle/DTFjKNZc8ZDaapkS7
from colleagues and friends (major engagement in the presentation)

### Notebooks

#### 01_get_info_from_survey 
Transformations from the survey results dataset into handy format for the other processes. Exported in csv

#### 02_get_summary_graphs
Sum of graphs summarising the survey result. Not the focus of the presentation, but expected to be asked

#### 03_get_cloud_of_words
For each user, create a cloud of words (genre of the movies seen X given rating), giving an impression of the "taste"

#### 04_get_users_heatmap
Calculate every distance between users, create a heatmap (triangle format)

#### 05_get_companion
Function: from a given user, gives n-closest users (out of the pool result)

#### 06_get_recommendation_from_a_friend
TO BE DEVELOPED
Function: out of a given user, provides recommendation of the movie from the closest "friend" (movies not seen by the other)
Add function of the genre

#### 07_get_users_cloud_pca
Attempt to plot 2D the suvey result together with MovieLens dataset. Not satisfactory results. Didn't make it to the presentation

#### 07b_get_cloud_pca_survey_data
Get 2D map plot based on PCA, only explains 29% of the variation


### Data
Collection of CSV used for the project

### Presentation
PDF based on Google Slides used in the presentation and pictures
