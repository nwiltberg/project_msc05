# Calendar week 1/2023 - goals & tasks

## Goals & tasks
- explain why I used correlation as connectivity measure
- download connectivity matrices from brainlife 
- implement unsupervised learning algorithm

## Completed tasks
- repeated course content about supervised and unsupervised learning and adapted comment about the Linear Support Vector Classification (1 hour)
- weekly meeting (1 hour)
    - installed brainlife in environment, login and created authorization token
    - used 'curl' to download the connectivity matrix for one subject 

## Problems
- need a authorization token to download data from brainlife
    - googled and checked https://brainlife.io/docs/technical/api/ & https://github.com/brainlife/auth (1 hour)
    - still don't understand how to get a token
    - SOLVED with Peer's help in weekly meeting but remaining problem:
        - to build a loop to download this file for every singe subject, a respective 'object number' for each subject is needed and I don't know how to get this number
        -> posted question in brainlife slack channel
- question: can I use clustering without specifiying the number of clusters?

## Goals & tasks for next week
- explain why I used correlation as connectivity measure
- download connectivity matrices from brainlife
- implement unsupervised learning algorithm