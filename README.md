
<b>CATEGORIZATION OF COLLECTION OF NEWS ARTICLES USING NLP</b>

In this project, I've used Python to process the textual content of a large collection of news articles with the goal of accurately predicting the correct category for all articles whose categories are currently unknown.

Term Frequency – Inverse Document Frequency (TF-IDF) scores for each news article was used for the categorization.

<u>Methodology</u>
There are multiple approaches to categorize the text. I've used the average TF-IDF feature vector for each article category. These average TF-IDF feature vectors are used as a basis for calculating the distance between each possible category and each article for which the category is unknown.
