# Multilingual-Product-Recommendation
In this project, my aim was to create a recommendation system for multiple languages. The system takes previously purchased items as input and predicts the next item to be purchased.
## Data
I have taken the data from one of the hackathons conducted on [AIcrowd](https://www.aicrowd.com/). You can find the datset [here](https://www.aicrowd.com/challenges/amazon-kdd-cup-23-multilingual-recommendation-challenge/problems/task-2-next-product-recommendation-for-underrepresented-languages/dataset_files).
Commands to add the dataset are provided in code.
## Model
In this project, I utilized content-based filtering to predict the next purchased item. The process involved preprocessing and encoding textual features. After which for each user, I calculated the cosine similarity between the features of their previously bought products and all available items. Based on the scores obtained, I predicted the top 100 items with the highest similarity scores as my prediction for the next item to be purchased.
