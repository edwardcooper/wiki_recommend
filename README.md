# Introduction
A data challenge to scrape and recommend wiki articles for a subcategory like medicine or physics.

A google slide describing the project is [here](https://docs.google.com/presentation/d/1KZ4o9n1m4-rQHxHemg2g3RrsXwNy8LgiL7nP21WG_nk/edit?usp=sharing)

Please see how much of the project you can complete in roughly 3 hours of work. Please plan to send your results to us in 72 hours, and don’t hesitate to reach out to us if you have any questions. Always send emails to ask questions if you have any and do not guess. 

# Task

1. Scrape 500 pages of a specific category on Wikipedia. For example, https://en.wikipedia.org/wiki/Category:Medicine

2. Build a graph where the nodes represent pages and the edges represent the semantic distance between those pages. Please keep just the 10 nearest neighbors for each node.

3. Create a visualization of your results. 

4. Please share your work with us (e.g. Jupyter notebook, etc.) with a brief write-up of your results.

# Results

The data folder contains the raw data scraped from the Wikipedia with the Physics category. 

The nlp_clean folder contain the data after data cleanining, and the notebook for visualizing the text data. 

The model folder contains the notebook to compare different models and vectorizers in terms of performance. 

The graph_vis folder contains the notebook to generate the network graph for the articles. 

