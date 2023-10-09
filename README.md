# kairanw.github.io

# MovieLens Data Science Project

## Introduction

The MovieLens dataset is a well-known dataset in the field of data science, particularly in the area of recommendation systems. It contains user ratings of movies, along with various user and movie attributes. This README file provides an overview of the dataset and the objectives of our data science project.

## Dataset

The original MovieLens dataset contained 100,000 ratings (ranging from 1 to 5) provided by 943 users for 1682 movies. Additional user information such as age, gender, occupation, and zip code, as well as movie information including title, release date, and genre, is included. It's important to note that each user had rated at least 20 movies, and the ratings were collected over seven months from September 1997 to April 1998.

The dataset we received has already undergone some cleaning, including the exclusion of users with fewer than 20 ratings and the removal of missing data. It consists of five separate CSV files:

1. **data.csv**: Contains the 100,000 ratings with corresponding user information.
2. **movie.csv**: Includes information on 1682 movies, including genre and release date details.
3. **genre.csv**: Provides a list of 19 genres.
4. **user.csv**: Contains demographic information for 943 users.
5. **occupation.csv**: Lists various user occupations.

## Problem Statement

The primary objective of our project is to understand how different user characteristics, such as age, gender, and occupation, influence movie preferences, as measured by user ratings in various movie genres. Ultimately, we aim to create a movie recommendation system that delivers personalized movie suggestions to users based on their demographic attributes.

## Hypothesis

Our hypothesis is that there exists a relationship between user demographic variables and movie preferences. Specifically, we believe that users with certain demographic characteristics are more likely to rate movies from specific genres more favorably than others.

## Approach

To address our problem statement and test our hypothesis, we have performed extensive data analysis, visualization, and machine learning modeling. Our primary target variable is the movie rating, and we consider user age, gender, and occupation as relevant variables. Zip code was excluded from our analysis due to practical considerations.

Our analysis seeks to uncover patterns and relationships between user demographics and movie preferences. We aim to build a machine learning model that can predict user ratings based on user and movie features.

## Conclusion

This MovieLens data science project explores the relationships between user demographics and movie preferences. By analyzing and modeling the data, we aim to create a recommendation system that enhances the movie-watching experience for users. Our findings will contribute to the field of recommendation systems and provide valuable insights into user behavior.
