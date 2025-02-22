# Questions to be answered in the analysis
## Completeness 
- **Density of nodes/edges/attributes (possibly grid-cell based?)**
- **If reference data set available: How 'much' of an area's cycling infrastructure is mapped?**
    - Total length/total length of different types of infrastructure
    - Development in contributions (spatial heterogeneity!)

## Quality
- **How well is it mapped?**
    - Customized simplification: tag diversity; parallel edges etc.
    - Differences in network structure
    - Differences in routing
    - Matching of data sets
    - Missing tags
    - Number of contributors
    - Contribution history

## Regional/local differences
- Point out areas that are possibly more "interesting": e.g. where number of edits is especially high/low, where number of contributors is high/low, where data sets differ strongly (include also: where infrastructure is more sparse?)


## Interpretation and Presentation of results
- Analysis of identified errors/inconsistencies - e.g. spatial clustering/autocorrelation - is there a tendency?
- Autogenerated summary and plots
- e.g. generate a PDF - each page contains a figure and an explanatory text. or keep it in notebook only

# TO-DO

## README

## Config

## Intrinsinc Notebook
- Plots + save plots 
- Simplification outcome
- Add references, edit explanations

## Extrinsic Notebook
- Polish texts, references and explanations 
- Plots + save plots

## Summary of findings
- **Friday**

## Feature Matching Notebook
- polish texts and plots

## Case Studies
- Run the analysis on 2 areas/2 reference datasets
- Make separate copies of all notebooks with results

## Paper
- Output
- Casestudies
- Abstract

## Before FOSS4G:
- Fix **all** plots (make nicer, some folium)
- Write tests for all functions
- Polish text and explanations to notebooks
- Documentation, environment
- Update README
- Make reference list for notebook refs
- remove matching functions from graph_functions.py etc.
- test reproducibility 

## NICE TO:
- Convert to simple graph in load data notebook?
- Small function for creating columns with index
- Small function for joining grids to data
- More advanced snapping - check if they share an edge or whether their one of their edges share a node with the other node.        Alternatively also check for edges within buffer distance, and whether there is a path to them within XX distance
- Functions for node over/undershoots
- For merge - check if col already exist - if it does - drop
- Replace create_cycling_network with nx.subgraph

## SMALL THINGS
- unconnected --> disconnected
- connected component first time, after than just components
- cycling --> bicycle
- EU reference