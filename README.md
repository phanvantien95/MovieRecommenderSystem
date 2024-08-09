# Movie Recommender System

This project implements a graph-based movie recommender system using the MovieLens dataset and Node2Vec algorithm.

## Overview

The Movie Recommender System analyzes user ratings to create a graph of movie relationships, then uses the Node2Vec algorithm to generate movie recommendations. It's designed to suggest movies based on user preferences and movie similarities.

## Features

- Data loading and preprocessing from MovieLens dataset
- Graph construction based on user ratings
- Visualization of the movie relationship graph
- Movie recommendations using Node2Vec algorithm

## Requirements

- Python 3.x
- pandas
- networkx
- matplotlib
- node2vec
- gensim
How it works

The system loads and preprocesses the MovieLens dataset.
It creates a graph where nodes are movies and edges represent how often movies are liked together by users.
The graph is visualized using matplotlib.
Node2Vec is applied to the graph to learn vector representations of the movies.
These vectors are used to find similar movies and make recommendations.

Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
License
This project is open source and available under the MIT License.
Acknowledgments

MovieLens dataset from GroupLens Research
Node2Vec implementation from the node2vec package
