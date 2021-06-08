# ODSC 2021: Reproducible and Automated Report Generation


This repository contains workshop material for the workshop "Reproducible and Automated Report Generation", which I gave at the Open Data Science Conference, Europe, 2021. 


:star: The R Markdown file **odsc-report.Rmd** provides a template to generate reproducible reports. 

:star: You can run the code and generate the report from within your browser with no need to install on your local machine the software package R, the RStudio IDE, a LaTeX distribution, Pandoc, or any of the R libraries that the template relies on.
  - :bulb: The runtime environment created for the Binder uses an MRAN snapshot of 2021-06-07 and relies on R version 4.1.0. 
  - :bulb: It may take a short time to launch the environment. 
  
  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jschultecloos/odsc_reproducible_reports/HEAD?urlpath=rstudio)  


## Workshop abstract

This workshop offers a gentle introduction to reproducible and elegantly formatted document generation with R Markdown. R Markdown presents a framework for reproducible workflows. It allows you to use multiple languages including R, Python, and SQL and helps you automate the production of HTML or PDF reports by relying on the power of Pandoc together with Lua-filters. Participants will learn how to implement literate programming practices to make their workflows fully reproducible and produce automated reports. We will first cover the basics of narrative text and code integration. Then, we focus on working on a template that is fully optimized for two different output formats, HTML and PDF. While in the stage of explorative data analysis and with an eye on content only, our template allows you to produce beautiful HTML reports of your analyses, optimized for the interactive exploration of your data. While in the stage of dissemination and with an eye on the presentation of results, our template allows you to produce beautifully typeset PDF reports, ready to be circulated or published any time.
