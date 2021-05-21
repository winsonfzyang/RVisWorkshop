---
title: "Prep"
nav: yes
---

# Workshop Prep

Please ensure that you have the latest version of R **and** R studio before coming for the workshop! Download the most recent versions of R and RStudio for the appropriate OS using the links below:

1. [R](https://cran.r-project.org/)
2. [RStudio](https://rstudio.com/products/rstudio/download/#download)

In the unlikely event that there are problems with installing R and R Studio, you can use RStudio Cloud, but you'll need **a laptop that can access the internet**.  

1. The set of relevant R packages, which you can install by connecting to the internet, opening RStudio, and running:  

    ```
    install.packages(
        c("remotes", "devtools", "rmarkdown", "knitr", "tidyverse", "kableExtra", "skimr",
        "haven", "readxl", "ggbeeswarm", "ggrepel", "xaringan", "DT")
    )

    remotes::install_github('yihui/xaringan')  
    remotes::install_github("rstudio/fontawesome")
    ```

In some cases for Windows users, you may encounter errors while installing some packages as you need Rtools installed. In that case, please install [Rtools here](https://cran.rstudio.com/bin/windows/Rtools/).


2. For best experience during the workshop, please have a second monitor or second display to follow along with the demonstration. If you do not have one, it is okay. You can also follow along with your copy of the materials.

To download the materials for this workshop, you have to go to this workshop's [repository](https://github.com/winsonfzyang/RWorkshop) and download the entire repository. Please take some time to look through the slides and/or content before the workshop.

Once you downlaoded the repository, click `RWorkshop.Rproj` to open the project workspace in RStudio. Then, please ensure that R Markdown is working properly. To do that, open the `00-Getting-started.Rmd` file located in the `handouts` directory. Then click *knit* to create a html document.


<img src="img/knit.jpg" width="400">

You should see a pop-up html website that looks like this:

<img src="img/knitted_doc.jpg" width="400">

If knitting is not successful, it might be that some packages are not installed or you're working with an incompatible R version. In any case, please send me an e-mail so we can work out a solution.


If you're a new R user, it's possible that installing R will be challenging. In that case, feel free to ignore the instructions and just count on RStudio Cloud. You can also contact me at [winson.yang@ttu](mailto:winson.yang@ttu.edu) before the workshop so we can troubleshoot together.
