# R Data Visualization Workshop

by WINSON YANG

-----

This repository contains all the resources for the R-Workshop.

To get start, you can either clone or download the repository.

-----

:spiral_calendar: July 13 and 15, 2021  
:alarm_clock:     03:00PM - 4:30 CT  
:hotel:           \[ZOOM\] (link provided after sign-up)

-----

## Learning Objectives
This is a two-day hands on workshop based on the book [R Graphics Cookbook](https://r-graphics.org). You will learn basic and advanced data visualization in R and learn some tips and tricks on creating plots, whether for a publication or a project. Along the way, you may encounter many packages and functions from the tidyverse including dplyr, tidyr, purrr, tibble, stringr, lubridate, and forcats.

As I know everyone is busy with work, research, and classes, this workshop is not meant to teach you the basics of R, but to share some best practices in data visualization in R. Hence if you want to learn more foundational R programming or data wrangling, please check out [R Workshop](https://winsonfzyang.github.io/RWorkshop) to get started. 


## Software Requirements
Please ensure that you have the latest version of R **and** R studio before coming for the workshop! Download the most recent versions of R and RStudio for the appropriate OS using the links below:

1. [R](https://cran.r-project.org/)
2. [RStudio](https://rstudio.com/products/rstudio/download/#download)

In the unlikely event that there are problems with installing R and R Studio, you can use RStudio Cloud, but you'll need **a laptop that can access the internet**.  

3. The set of relevant R packages, which you can install by connecting to the internet, opening RStudio, and running:  

    ```
    install.packages(
        c("remotes", "devtools", "rmarkdown", "knitr", "tidyverse", "skimr",
        "readxl", "ggbeeswarm", "ggrepel", "xaringan", "DT")
    )

    remotes::install_github('yihui/xaringan')  
    remotes::install_github("rstudio/fontawesome")
    ```


In some cases for Windows users, you may encounter errors while installing some packages as you need Rtools installed. In that case, please install [Rtools here](https://cran.rstudio.com/bin/windows/Rtools/).

If you're a new R user, it's possible that installing R will be challenging. In that case, feel free to ignore the instructions and just count on RStudio Cloud. You can also contact me before the workshop so we can troubleshoot together.



# Resources

These are some resources to get you start or continue learning R or ggplot. The list is non-exhaustive; as I find more interesting resource, I will put them here.

[RStudio Cheat Sheets](https://rstudio.com/resources/cheatsheets)<br/>
[R-graph-gallery](https://www.r-graph-gallery.com/index.html)<br/>
[ggplot documentation](https://github.com/erikgahner/awesome-ggplot2)<br/>
[ggplot2 book](https://ggplot2-book.org/)<br/>
[UCLA's Statistics Consulting Group](https://stats.idre.ucla.edu)<br/>
[R for Data Science](https://r4ds.had.co.nz)<br/>
[R for Psychological Science](http://psyr.djnavarro.net/)<br/>
[Data Science for Psychologists](https://bookdown.org/hneth/ds4psy/)<br/>
[Teacups, giraffes, and statistics](https://tinystats.github.io/teacups-giraffes-and-statistics/)<br/>


## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a>

Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/rstudio-education/master-the-tidyverse" rel="dct:source">https://github.com/rstudio-education/master-the-tidyverse</a>, [https://github.com/cwickham/data-science-in-tidyverse](https://github.com/cwickham/data-science-in-tidyverse), and [https://github.com/AmeliaMN/IntroToR/](https://github.com/AmeliaMN/IntroToR/)
