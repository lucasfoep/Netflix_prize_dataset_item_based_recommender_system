# Netflix prize dataset item based recommender system

### What does it do?

It builds an item-based (rather than user-based) recommender system for the Netflix Prize dataset.

### What were the tools used?

- Pandas
- Numpy
- Matplotlib
- Scikitlearn

### Why have I made it?

While taking a machine learning class for my masters in Data Science at DePaul I had the opportunity to create a recommender system. Instead of creating a user-based recommender system I decided to experiment with an item-based one to see how it would compare. I also decided to test TF-IDF as an input for the best model created (KNN + SVD) hoping to highlight relevant patterns by focusing on significant interactions rather than on the entire, massive, and sparse, data matrix. This was an experiment driven by curiosity, but it did improve the MAPE for the best model.
