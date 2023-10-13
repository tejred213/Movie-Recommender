<h1 align='center'> Movie Recommender System </h1>
<h2 align='center'> https://movie-recommender-system-21.streamlit.app/</h2>
<br>
<p>In this project, I have built a content based movie recommender system. The algorithm recommends products that are similar to the ones that a user has liked in the past. This similarity (generally cosine similarity) is computed from the data we have about the items as well as the user’s past preferences. </p>
<br>
<p align='center'> <img height='400' src = 'https://github.com/tejred213/Movie-Recommender-System/assets/86062873/c577db73-7d4c-4314-ae09-406ab827f768'></p>
<br>
<h2> Live Demo </h2>
<p align='center'><img height='400' src = 'https://github.com/tejred213/Movie-Recommender/assets/86062873/ff536974-a8be-4b49-8e17-2740fc7eaf54'></p>

<br>
<h2>Basic Functioning</h2>
<p align='center'> <img height='400' src = 'https://github.com/tejred213/Movie-Recommender-System/assets/86062873/00953236-25c6-4e7a-8d6e-68b9aaf887a4'> </p>
<br>
<h2>How does it work : </h2>
<p>Content Based Filtering - They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.</p>
<br>
<h2>How to get the API key used in this project for images ? </h2>
<p>Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.</p>
<p align='center'> <img src = 'https://github.com/tejred213/Movie-Recommender-System/assets/86062873/6ffc2123-0d76-410f-b8d5-54527eed1aa3'></p>

<br>

<h2>Similarity Score : </h2>
<p>How does it decide which item is most similar to the item user likes? Here we use the similarity scores.
<br>
It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.</p>
<p align='center'><img src='https://github.com/tejred213/Movie-Recommender-System/assets/86062873/50894377-584a-4b9c-8742-4a9bbce1263f'></p>
<br>

<h2>How does Cosine Similarity work ? </h2>
<p>Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.</p>
<p align='center'><img src='https://github.com/tejred213/Movie-Recommender-System/assets/86062873/c3c6296f-ba4c-47f1-a793-9b68396ba442'></p>
<br>
<h2>Sources of the datasets : </h2>
<p>I have used the TMDB 5000 movies dataset to build the model</p>
<p>You can collect dataset from https://www.kaggle.com/tmdb/tmdb-movie-metadata</p>

