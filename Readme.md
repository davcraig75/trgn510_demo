# Lecture on Data Science Notes

Interactive day today.
[davcraig75/trgn510_demo](https://github.com/davcraig75/trgn510_demo.git)

## Using Markdown and other Tools

Examples shown in a list.

* **Making something bold**
* _Underlining_
* What type of list is this?

Steps

1. Start computer
2. This is an ordinal list

Very important:  `This is meant be formatted so that it could indicate code inline`

The other type of code is a **code block**

``` {brush: bash}
ls
ls -l
test 
```
End of code block

## Data Communication Graphing & Types

### Initial Question: What form is my Data

##### Table: What do rows represent. What does it represent

Ideally the first column of a table is UID.  There are UIDs - something that is unique to a project.  A GUID is something that is unique globally.

##### What are the other types of column based data?

Many have data dictionaries that provide this.

###  Exploring Data Visually To Understand

We will use this website - [Exploration of dataset](https://www.bioinform.io/trgn.html)

#### What are key objectives in Graphing

Core libraries: D3.js, Plotly, ggplot2, vega.js highcharts, echarts.

* Explore data visually
* Interactivity
* Make argument or show a point

## Graphing Styles

### Contours, faceting

In this example, I'm looking at several variables simultaneously.  X-axis is continious, as is my Y-axis. This means that we are looking at scatter, heatmaps and contour plots.  We would not expect a violin example.  We have a lot of discrete data and 10,000 points.  How do we manage that?  Histograms but also contour plots and so forth.

![](https://res.cloudinary.com/itgusc/image/upload/v1630617486/Graphs.png)

##  Dimensional reduction

A few we will be talking over the next few weeks is PCA, tSNE, UMAP.  Overall their goal is to help with visualziation of multidimensional data in a way that accounts for the most variability.

A great fun way to understand something tSNE [at this link](https://distill.pub/2016/misread-tsne/).

## Deterministic vs Non-deterministic

If I ran the same program again, would I get the same identical result.  Historically, this was always the case.  Pre-2015.  Post-2015 many algorithm are not.

