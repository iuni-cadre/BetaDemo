---
title: "Demo02: Reproducibility and Network Visualizations (Yan)"
teaching: 15
exercises: 0
questions:
- "How can you build networks from query results and visualize them"
objectives:
- "Demonstrate DOI featured packages and how the Market will integrate"
- "Demonstrate network visualizations."
- "Explain how you can reproduce the result using public tools, with your own data"
keypoints:
- Visualize prepared data query data in notebook
- Visualize your query data without coding by using featured packages
- Refine your query for better visualizations
---

> ## Getting Started
>- Start your Jupyter Notebook from [https://cadre.iu.edu/gateway/jupyter](https://cadre.iu.edu/gateway/jupyter)
>- To get the input files in the right path, run the "demo02_data_package" from the CADRE Marketplace. [https://cadre.iu.edu/gateway/rac](https://cadre.iu.edu/gateway/rac)
{: .prereq}

## Scripts and Notebooks
Notebooks and source code will be automatically downloaded to your personal Jupyter Notebook. They can also be found at the [GitHub repository](https://github.com/iuni-cadre/BetaDemoCode).

Demonstrate DOI featured packages at
https://cadre.iu.edu/resources/dois/sdg-research

The following script illustrates the reproducible code for building coauthor network from the orginal data courtesy of the Fellow team "Mapping Collaborations and Partnerships in SDG Research"
```
Notebook:  BetaDemoCode/Demo 02/MCAPcoauthor.py
```

The following notebook illustrates how to transform your own query results for a similar visualization
```
Notebook:  BetaDemoCode/Demo 02/CustomQuery.ipynb 
```

The second script translates the code in the aforementioned notebook and produces a sharable package
```
Notebook:  BetaDemoCode/Demo 02/CustomQuery.py
```
## CADRE packages and tools
All packages, tools and archives can be accessed from the CADRE Marketplace. [https://cadre.iu.edu/gateway/rac](https://cadre.iu.edu/gateway/rac)

The following package will reproduce the coauthor network by the Fellow team "Mapping Collaborations and Partnerships in SDG Research".
```
Package:  https://cadre.iu.edu/gateway/rac/package/a7f1929d-0262-4f0a-b728-a1e42654d88c
```

Use the following public tool to create new packages for your own query results.
```
Tool:  Custom Coauthor Network
```

> ## Current limitations
>- Only Microsoft Academic Graph data is compatible with this demo
>- Refine your query size for better visulization results (especially graph size control)
>- Public sharing of user tools, and packages, archive sharing will be enabled later
>- Advanced visualizations in Notebook Part2.ipynb currently cannot be containerized into CADRE packages or tools
{: .callout}

{% include links.md %}
