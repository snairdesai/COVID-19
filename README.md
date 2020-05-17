# Accounting for Global COVID-19 Diffusion Patterns, January-April 2020

*Tracing the relationship between government interventions to the pandemic and the mortality curve.*

This repo stores input, output, and code for the May 2020 NBER Working Paper "Accounting for Global COVID-19 Diffusion Patterns, January-April 2020" by Yothin Jinjarak (Victoria University of Wellington); Rashad Ahmed (University of Southern California); Sameer Nair-Desai (University of Southern California); Weining Xin (University of Southern California); and Joshua Aizenman (University of Southern California).

The master branch hosts the R Markdown and Knitr documents, as well as folders with the initial data; temporary data; visualizations (interactive and static); and regression outputs.

# DESCRIPTION OF THE FILES

The relevant R Markdown file is "COVID-19_Country_4-30-20.rmd" which is fully reproducible in RStudio or RCloud. Accompanying the markdown are knitted files of the output ("COVID-19_Country_4-30-20.knit.md"; "COVID-19_Country_4-30-20.html"; COVID-19_Country_4-30-20.utf8.md").

# DESCRIPTION OF THE FOLDERS

The "data" folder includes all of the initial and manipulated data used in the analysis. Details on where the data was pulled from can be found in the relevant chunks of the Markdown file, in the text documents of the working paper, and in the associated README file. Credit for the data goes to all associated sources, which are cited in the paper.

In addition to the data folder, the repository also hosts the "csse_covid_19_time_series", "government_data", and "spatial_data" folders. The data from these folders is also uploaded to the central data folder, but have been included separately for ease of access. These represent our primary raw data files. The first file contains the COVID data pulled from John Hopkins CSSE. The second file contains the government data pulled from the Oxford Government Response Tracker. The last of these folders (spatial_data) was not included in this version of the working paper, but will be used in subsequent rounds of analysis.

The "output_html" folder includes all of the interactive figures constructed through Plotly; which can be opened in a web browser for user interaction.

The "output_png" folder includes all of our static figures.

The "reg_output" folder includes all of the tables from the regression analysis, which have been clearly labelled for ease of access. You will be able to find where the tables are generated in the markdown file by using the search function.

There are also two files (both as Markdowns and knitted HTMLs), detailing the text of the working paper ("COVID-19_texts.rmd"; "COVID-19_texts.html") and analysis/figures included in the paper ("COVID-19_numbers.rmd"; "COVID-19_numbers.html"). These are located in the "text" and "analysis" folders respectively.

For convenience, an additional folder ("previous_versions") has been uploaded with prior versions of the markdown file, and the initial plans for analysis.

All folders in the repository are accompanied by a detailed README file explaining the contents.
