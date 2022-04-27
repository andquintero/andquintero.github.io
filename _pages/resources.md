---
title: "Andres - Resources"
layout: textlay
excerpt: "Andres -- Resources"
sitemap: false
permalink: /resources/
---

# Resources

Here you can find some of the tools and pipelines I have contributed to develop. 

## Pipelines for processing of bulk data

I have been involved in the developed of Snakemake pipelines that allow the user to process raw files (fastq) until a final html report, containing basic quality-control statistics, as well as downstream analyses (e.g., footprinting analysis for ATAC-seq data, peak enrichment por ATAC-seq and ChIP-seq).

All the instructions of how to use the pipelines can be found in the following GitHub repositories:

- [Bulk ChIP-seq pipeline](https://github.com/hdsu-bioquant/pipelines-chipseq)
- [Bulk ATAC-seq pipeline](https://github.com/hdsu-bioquant/pipelines-ATACseq)

---


## ShinyButchR - Interactive NMF toolbox
![]({{ site.url }}{{ site.baseurl }}/images/respic/slider_butchr.png){: style="width: 50%; float: left; margin: 0px  10px"}

ShinyButchR is an interactive application to execute an NMF-based workflow from start to end. The results obtained with ShinyButchR can be imported into R to perform feature extraction and other downstream analyses.

The app is publicly available [here](https://hdsu-bioquant.shinyapps.io/shinyButchR/), and we also provide a [Docker image](https://hub.docker.com/r/hdsu/shinybutchr) to allow its execution and deployment in local servers.


<div class="special-class" markdown="1">
</div>{: style="clear: both"}
---



## MapMyCorona


![]({{ site.url }}{{ site.baseurl }}/images/respic/map_my_corona_logo.png){: style="width: 50%; float: right; margin: 0px 10px"}
The current SARS-CoV-2 pandemic has shown an impressive speed of spreading throughout the world. One of the main challenges is to understand how the viral sequence is evolving day by day. There are now multiple strains that are active at the same time, and keeping track of the population dynamics is not an easy task.
In order to address these challenges, we joined in the world effort to fight COVID-19 by developing [MapMyCorona](https://hdsu-bioquant.shinyapps.io/mapmycorona/) to display in an easy way, the sequence similarity and alterations between a query sequence and a central database of viral SARS-CoV-2 sequences on a world map.






