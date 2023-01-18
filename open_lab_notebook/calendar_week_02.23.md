# Calendar week 2/2023 - goals & tasks

## Goals & tasks
- adapt notebook according to the feedback (pull reqest)
- explain why I used correlation as connectivity measure
- download connectivity matrices from brainlife 
- implement unsupervised learning algorithm 
    - find out how to implement clustering without specifying the number of clusters (clarified in weekly meeting)
    - use 'kmeans' in several passes with differing number of clusters
    - use silhouette_score to check which number of clusters fits the data best

## Completed tasks
- read alot about Support Vector Machines (to be able to explain, how I applied them - 1 hour)
- read about different clustering methods here: https://scikit-learn.org/stable/modules/clustering.html (30 min)
- adapted comment about LinearSCV (15 min)
- weekly meeting (1 hour)
- implemented an unsupervised learning algorithm using KMeans (30 min)
- read about function [silhouette_score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.silhouette_score.html) and searched the web for examples to understand what the function does (1 hour)
- implemented a loop for several runs of KMeans and the computation of the silhouette score, plotted and described the results (1 hour)
    (first had some trouble with the loop, and needed to adapt it several times)

## Problems
- question: how do I know I if my data is linearly separable in order to decide if I can use a linear SVM?
    SOLVED: talked about it in the weekly meeting 
            -> first possibility: make a decision based on assumptions about the data 
                second possibility: plot only the correlations of two of the seven extracted networks and check if the groups can be linearly separated only looking at them 
- unsure which clustering method fits my data 
    SOLVED: talked about it in the weekly meeting
            -> use 'kmeans' and do several passes with different numbers of clusters, then use silhouette_score to check which number of clusters fits the data best

## Goals & tasks for next week
- download connectivity matrices from brainlife
