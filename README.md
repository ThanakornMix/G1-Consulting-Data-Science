# G1-Consulting-Data-Science

### Overview 

This Project aims to analyze publication trends, citation impacts, and collaboration networks within CDKN2A research, with a focus on oncology and cancer studies. Using datasets on articles, authors, and publication counts, it identifies active researchers, investigates co-authorship patterns, examines geographical distributions, and explores trends in journal publictaions and cancer-related gene CDKN2A research. Through data science methodologies and visualizations, this project provides actionable insights to advance understanding in this field.

### File Descriptions

#### Consulting.ipynb - 

This provides a comprehensive analysis of co-authorship networks and publication trends. It identifies the most active researchers in this gene therapy field, explores their collaboration patterns, and visualizes these as a network graph. This also delves into trends in publication activity over time, focusing on key contributors and their preferred journals. Additionally, it examies topic development, such as the intersection of CDKN2A with cancer research, and highlights institutions leading in this domain.

#### Geographical_Distribution.ipynb

It Analyses the locations of authors and institutions contributing to the field, highlighting regional research hubs and collaborations. Visualizations such as heatmaps and geographical plots provide insights into how research is distributed globally, identifying regions with significant contributions or emerging research activity

#### Citatioin_Counts.ipynb - 

This focuses on analyzing citation data to evaluate the impact of publications related to CDKN2A research. It includes detailed visualizations and metrics to identify highly cited works, trnds in citation counts over time, and their distribution across jpournals anf researchers. This analysis helps highlight influential papers and their contributions.

### Datasets 

#### articles.CDKN2A.csv - 

Contains details about articles, including authors, abstracts, locations, and publictaion metadata related to CDKN2A.

#### authors.CDKN2A.csv -

Includes information about authors contributing to CDKN2A research, such as names and affiliations.

#### paper_counts.csv -

Summarizes the total number of publications over time, providing a broader view of research activity.

### Features 

#### Data Analysis 

Citation Trends: Identifies patterns in citation counts across years.

Author Contributions: Highlights key contributors to CDKN2A research.

Geographical Insights: Visualizes the regional focus of publications.

#### Data Processing 

Cleaning: Handles missing and incosistent data. 

Aggregation: Summarizes data for visualization and intrepretation.

#### Visulizations

1. Trends in CDKN2A research over time
2. Geographical Distribution of Publications
3. Top Institution in the Field
4. Publication Trends of Top 15 Researchers 
5. Co-Authorship network
6. Top 10 Journal Publications 
7. Proportion of Cancer Realted Publication in Top 10 Journal
8. Top Cited Researcher ID's

### Dependencies 

Python version: 3

Required Libraries:

          pandas,
          numpy,
          matplotlib,
          seaborn,
          plotly,
          geopandas,
          itertools,
          networkx,
          crossref,
          pycountry
          
          
          
          
