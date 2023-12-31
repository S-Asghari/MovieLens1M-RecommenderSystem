In this repository, I implemented a recommender system for movies as my Data Mining course project (CSC503). 

For this purpose, I used the [MovieLens 1M dataset](https://grouplens.org/datasets/movielens/1m/).

Inspired by [Toby Segaran's text book](https://books.google.com/books?hl=en&lr=&id=fEsZ3Ey-Hq4C&oi=fnd&pg=PR13&dq=Segaran,+Toby.+Programming+collective+intelligence:+building+smart+web+2.0+applications.+%22+O%27Reilly+Media,+Inc.%22,+2007.&ots=Sg08VXN-Ec&sig=PjUQvwLsOx2Jbt78xT3kEYTTYnY), I implemented the user-user and item-item collaborative filtering methods. I tried different similarity metrics such as Euclidean distance, cosine similarity, and Pearson correlation similarity.

Moreover, I implemented the mean and biases baseline predictor based on [a research paper by Yehuda Koren and Robert Bell](https://link.springer.com/chapter/10.1007/978-1-0716-2197-4_3).

In the end, I evaluated all methods using RMSE. For more details about the RMSE results, please refer to ml_1m.ipynb file.
