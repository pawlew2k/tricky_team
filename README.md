# tricky_team

## Description

Program for determining the shortest paths between matches of the national football team. \
The shortest path has the fewest matches that team A is able to defeat indirectly team B. \
For example: \
A> X \
X> Y \
Y> Z \
Z> B, where '>' means the win of the first team

## Data source

All FIFA matches are taken into account (from 1872-11-30 to 2021-12-11). On their basis, the smallest number of matches is determined.

https://www.kaggle.com/martj42/international-football-results-from-1872-to-2017 

## Libraries used
- [igraph](https://igraph.org/python/tutorial/latest/tutorial.html)
- [pandas](https://pandas.pydata.org/docs/user_guide/index.html)
- [numpy](https://numpy.org/doc/stable/user/index.html#user)
