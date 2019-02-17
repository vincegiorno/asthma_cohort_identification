# asthma_cohort_identification
Identification of study cohort from curated, de-identified data. The repo contains Jupyter notebooks in Python and R that select candidates for a study using specified criteria and data provided in .csv files. The data cannot be made public.

The primary selection mechanism in the Python notebook is SQL queries, whereas the R notebook loads the data into dataframes first, and then filters and joins the records. The identified cohorts are identical except for one record that was incorrectly included based on the SQL queries. R provided a more straightforward interface, although the data.table syntax is less declarative and harder to follow than if dplyr had been used as the main data manipulation package.  
