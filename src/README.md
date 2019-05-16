This subfolder contains source code for the data acquisition for this project. `raw_to_mrc.R` contains the code for querying, transforming, and tidying of the data from IPEDS, as well as the join to the Mobility Report Card Data (`mrc_table1.csv`) from Opportunity Insights. `colleges_to_shiny.R` contains the source to make a cleaner-looking version of `colleges_mrc.Rda` to use in the front-end of the app. `codebook_script.R` gives the code to generate the data codebook found in `shiny/shiny_codebook.R`. `tables_16.xlsx` and `varnames.csv` are utilized in `raw_to_mrc.R` to query and transform the IPEDS data.

To read more about our project and methods, see `paper.pdf` in the parent folder.