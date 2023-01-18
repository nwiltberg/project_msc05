# Calendar week 3/2023 - goals & tasks

## Goals & tasks
- explain why I used correlation as connectivity measure
- download connectivity matrices from brainlife 
- go through github review
    - check https://peerherholz.github.io/ns_ac_walkthrough/clustering.html#cluster-evaluation
    - adapt clustering according to review -> use [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)
    - add a plot for each cluster, coloring the datapoints based on the label of the respective participant 
        -> discussed in meeting that this it's not really possible to plot the cluster this way because the data contains correlations between 7 networks -> discarded
- explore results of the clustering (see below)



## Completed tasks
- weekly group meeting (1 hour)
- checked: https://peerherholz.github.io/ns_ac_walkthrough/clustering.html#cluster-evaluation (15 min.)
- weekly 1-1 meeting (30 min.)
    - talked about GridSearchCV and possibilities to explore clusters:
        - plot mean correlation matrices for each cluster
        - compute difference between the mean correlations to see which connections differ the most
        - use a scatterplot (y-axis: connection, x-axis: correlation) -> 21 datapoints for each subject -> color the points according to cluster
        - maybe there is a maximum of three connections that should differ in particular, based on theory -> plot only these connections 
- read about [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html) (15 Min.)
- tried to implemend GridSearchCV but run into warnings and errors (see below) (30 Min.)


## Problems
- grid.fit resulted in a warning: "one or more of the test scores are non-finite"

## Goals & tasks for next week
- 
