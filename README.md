# Spending on Education in the US

This repo contains the code to re-create my entry into [RStudio's Table Contest for 2020](https://blog.rstudio.com/2020/09/15/announcing-the-2020-rstudio-table-contest/).

For full details on the data and a step-by-step guide on how I customised the table, please see my blogpost: [https://davidsmale.netlify.app/portfolio/spending-on-education/](https://davidsmale.netlify.app/portfolio/spending-on-education/)

Data was processed using the {tidyverse} packages, and the table was built with the {gt} package.

This repo contains 3 files:

*  `education_spend_table.R` - The code to read-in and process data and render a table in HTML
*  `education_spend_table_png.R` - Almost identical to the above, but with minor changes to render table as a png file. The minor changes include:
    *  Lightening the background of the ggplots because otherwise these backgrounds were being rendered too dark.
    *  Changing font of the source note using `opt_table_font`. I found this was the only to adjust font of source note. However, on my blog this option was still being overwritten by the default font of my blog.
*  `education_spend_table.png` - The rendered png of the table:

<p align="center">
  <img width="300" src=https://github.com/committedtotape/education-spending/raw/main/education_spend_table.png">
</p>
