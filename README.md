# datavisexp-agora
 <h3>What's this?</h3>
This repository hosts the project which has been developed as part of the university course **Data Visualization and Exploration**, which teaches dataset exploration techniques
using the R language.
Requirements of such project were the following:

* Select one or more data sources. You should find one or more datasets that are interesting for you. You are free to pick any dataset you prefer.
* Describe what the datasets are about and what you expect to find during the exploration.
* Clean and preprocess the dataset, recording the reasoning behind your preprocessing choices in the report.
* Visualize different aspects of the dataset using the most appropriate visualizations we study in the course.
* State your findings.

I created this repo to both back-up my project and as a future reference for myself or for anyone who could be interested in the argument.

 <h3>Project description</h3>
"Agora" was one of the largest darknet markets, and was active from 2013 to 2015. 
It operated primarily as a black market, allowing transactions of illegal items and services such as drugs, weapons, stolen/fake documents, cyber arms and other.
The dataset under analysis is a [Kaggle dataset](https://www.kaggle.com/philipjames11/dark-net-marketplace-drug-data-agora-20142015) 
created from a raw html rip of the Agora website in years 2014/2015.
The Kaggle dataset curator states that he obtained the data from a 3rd party source, but acknowledges its origin from the [Darknet Web Archives](https://www.gwern.net/DNM-archives), 
a huge collection of scraped/mirrored data from the Dark Net Markets between years 2013-2015 and used as a reference from many papers related to studies on darknet markets. 

The exploration of this dataset could lead to some interesting findings. Examples are potential correlations between different illegal items and from their shipping origin/destination, price estimate in certain regions in the world and identifying high risk regions or vendors.

**DISCLAIMER: darkweb is a treacherous dimension, and most of transaction on darknet markets involve illegal items. The following does not intend neither to encourage illegal activities in any way, nor to promote reckless darkweb surfing. 
Rather, it aims to perform an analysis to try to identify the behaviours and characteristics of one of the biggest of such market platforms.**


<h3> Files description </h3>
The project is a notebook created with RStudio. An R Notebook is an R Markdown document with chunks that can be executed independently and interactively, and it can be rendered in different formats such as .pdf or .html.
* *Project.Rmd* is the actual source file
* *Project.nb.html* is the rendered file created upon compilation
* *renv.lock* contains the dependencies of the project. It can be used to restore them via the *renv* tool.
