# Movielens Dataset Analysis on Azure

Movielens Dataset Analysis on Azure — AWS Data Engineering project.

## Overview
In this project,we shall implement a comprehensivedata pipeline to process, analyze, and derive movie recommendations using the Movielens dataset on Microsoft Azure. The goal is to transform unstructured raw movie data into actionable insights, helping users discover relevant content while enabling data-driven product improvements. Designed within a cloud-based, scalable architecture, this pipeline ensures seamless orchestration, efficient transformation, and high-performance analytics.

T his project presents a robust, end-to-end Azure-based data pipeline that performs standardized dataset analysis and recommendation using Spark and Python. By leveraging services like Azure Blob Storage, Data Factory, and Azure Databricks, the pipeline provides a reliable framework for handling large-scale data, enabling effective movie recommendations and visualization of user preferences.

Use Cases for the Proposed Pipeline

## Data
T his project involves working withreal-world datasets:MovieLens Dataset– A CSV-based dataset from GroupLens Research containing user ratings and metadata for movies, containing rich information about movies, ratings, and reviews.

T he MovieLens dataset is comprised offour CSV files,each playing a unique role in understanding movie metadata, user preferences, and interaction patterns:

The dataset is composed of four main CSV files:

1. links.csv

This file maps MovieLens movies to external databases like IMDb and TMDb.

- movieId– Unique identifier for each movie used throughoutthe dataset
- imdbId– Corresponding IMDb ID
- tmdbId– Corresponding TMDb ID

2. movies.csv

This file provides descriptive information about each movie.

- movieId– Unique movie identifier
- title– Movie title along with its release year (e.g.,"Toy Story (1995)")
- genres– Pipe-separated genres associated with themovie (e.g., Action|Comedy|Drama)

MOVIELENS DATASET ANALYSIS ON AZURE

3. ratings.csv

This file records explicit user ratings for movies.

_Data is not included in this repository._

## How to run
Notebooks: [`Algorithm.ipynb`](Code/Algorithm.ipynb), [`Authorization.ipynb`](Code/Authorization.ipynb)

## Project structure
```
.gitignore
Code/
  Algorithm.ipynb
  Authorization.ipynb
README.md
```

## Credits
Based on a ProjectPro guided project.
