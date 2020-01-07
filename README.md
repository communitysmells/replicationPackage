# Learning to Detect Community Smells

This repository is a companion page for our submission "Learning to Detect Community Smells".

It contains all the material required to replicate our analysis, including (i) the raw input data (ii) the list of studied projects with their repository links in GitHub, and (iii) the metrics formulation with their equations. Some additional data are not included in the paper due to space limitations, are also provided.

### Data description : 
The data is presented in CSV format and can be directly imported in R and Weka.

```Projects_list.csv```: The summary of all the raw projects.

```Dataset.csv```: The list of projects with their metrics values and identified smells.

```Metrics formulation.pdf```: The formulation of the new used metrics

#### Developer Social Network metrics  

```NoD ```: Number of developers

```TAP``` : Number of active days of an author on a Project

```LCP``` : Number of changed lines of a code per author in a project

```CD``` : Number of core developers

```RCD``` : Ratio of core developers

```SD``` : Number of sponsored developers

```RSD``` : Ratio of sponsored developers


#### Social Network Analysis metrics 

```DC``` : Graph Degree centrality

```BC``` : Graph Betweenness centrality

```CC``` : Graph Closeness centrality

```ND``` : Network Density


#####  Community metrics 

```NC``` : Number of communities

```RCC``` : Ratio of commits per community

```RDC``` : Ratio of developers per community

####  Geographic Dispersion metrics 

```TZ``` : Number of time zones

```RCZ``` : Ratio of commits per time zone

```RDZ``` : Ratio of developers per time zone


####  Formality metrics 

```NR``` : Number of Releases in a project

```RCR``` : Ratio of Commits per Release 

```FN``` : Formal network


####  Truck Number metrics 

```BFN``` : Bus Factor Number

```TFN``` : Truck Factor Number

```TFC``` : Truck Factor Coverage


