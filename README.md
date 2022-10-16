# Movie-Recommendation-System
Recommendation systems use a class of algorithms that can suggest relevant items to the users. This Movie Recommendation system built using multiple ML models aims to predict users' interests based on their past behavior and preferences.

# Demo
[https://www.youtube.com/watch?v=1xtrIEwY_zY&t=6911s](https://drive.google.com/file/d/1iWC2IeHA4d0M7UU-EB1LryINuVM130qq/view?usp=sharing)

# Similarity Score :
How does it decide which item is most similar to the item user likes(or selects in our case)? Here comes the similarity scores.

It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

# How Cosine Similarity works?

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

![70401457-a7530680-1a55-11ea-9158-97d4e8515ca4](https://user-images.githubusercontent.com/91384498/196020904-32f78aab-7e88-4838-8a1c-4664f0f154f9.png)
