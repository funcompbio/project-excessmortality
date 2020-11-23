# Project excess mortality - FCB 2020

## Summary

In this project you should analyse data to attempt answering the following question:

> Is public health expenditure (%GDP) associated with the excess mortality rate observed during the COVID19 pandemic?

## Data

You should use the following two datasets:

1. The excess mortality data for the period covering the 2020 COVID19 pandemic collected
by the [Financial Times](https://www.ft.com) and available
[here](https://github.com/Financial-Times/coronavirus-excess-mortality-data). The dataset
is in a CSV file called `ft_excess_deaths.csv`.

2. Public health expenditure (%GDP) data available through the data portal
[Our World in Data](https://ourworldindata.org)
[here](https://ourworldindata.org/grapher/public-health-expenditure-share-gdp-owid).
Use the link `Download` to download a CSV file with the data.

## Deliverables

The GitHub repo for this project should contain, at least, the following files:

  * `index.Rmd`: R Markdown script with the R code doing the analysis of the data
    and the corresponding text explaining those analysis steps.
  * `index.html`: Resulting HTML output from processing (_knitting_) the file
    `index.Rmd`.
  * The CSV files employed during the analysis.

The analysis of the data described in the HTML file should contain the following
sections:

  * **Abstract:** Summary of the question and the findings (max. 200 words).
  * **Introduction:** Description of the question and the data employed to answer it.
    Description of any steps taken, if any, previous to this R Markdown document,
    to prepare the data that is being analyzed.
  * **Results:** R code intertwined with text, descriping the analysis steps and the
    display items with the results, which should consist, **at least**, of one table
    and one plot.
  * **Conclusions:** summary of the findings, limitations of the study, ways in which
    this type of study could be improved in the future.
  * **References:** bibliographic references.

## Methodology

The analysis of the data should be carried out at least using R, but you can also
use shell or Python scripts to transform or prepare the data for the analysis with
R. If those prior steps using shell or Python scripts are included, they should be
described in the introduction section of the R Markdown document and, ideally,
made readily reproducible using a Makefile.

## Evaluation rubric

The rubric to evaluate this project consists of the following items:

* Does the GitHub repo contain at least the analysed CSV files along with the
  `index.Rmd` file and the resulting `index.html`?

* Does the R Markdown file `index.Rmd` run the analysis without errors and
  generates the expected `index.html` file?

* Does the analysis described in the resulting `index.html` file conform to
  the requested sectioning.

* Does the introduction explain clearly what is the question addressed, the
  data employed and the number of observations and variables involved?

* Do the plots show some meaningful summary of the data? Are axes in plots
  labeled in plain language and large enough to read?

* Does the GitHub repo include a _Makefile_ that automatizes the entire analysis
  pipeline and generation of the final report in the `index.html` file?
