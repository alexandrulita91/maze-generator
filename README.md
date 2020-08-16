# Maze generator
A maze can be generated by starting with a predetermined arrangement of cells with wall sites between them.

## Requirements
- [Python 3.6 or 3.7](https://www.python.org/downloads/release/python-360/)
- [Pipenv](https://pypi.org/project/pipenv/)

## How to install the packages
You can install the required Python packages using the following command:
- `pipenv sync`

## Depth-first search
Depth-first search (DFS) is an algorithm for traversing or searching tree or graph data structures. The algorithm starts at the root node (selecting some arbitrary node as the root node in the case of a graph) and explores as far as possible along each branch before backtracking.

## Parameters
- **screen_width** - window width
- **screen_height** - window height
- **nx** - number of maze lines
- **ny** - number of maze columns

## Important
Ensure that you can do the following before you run the maze generation:
- **screen_width** can be divided by **nx** and get rest 0 
- **screen_height** can be divided by **ny** and get rest 0 

## How to generate the maze
You can generate the maze using the following command:
- `pipenv run python depthfirst.py`

## Demo video
https://www.youtube.com/watch?v=aCQoM1mUTog

## Improvement ideas
- improve the code quality
- remove unnecessary comments
