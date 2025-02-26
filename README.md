# PhytoCytoTraits

This programme aims to sort automatedly flow cytometry traits through a user friendly graphical interface. The application provide basic but complete pipeline for flow cytometry data, from QA-QC to unsupervised classifications.

## Installation

**R environment**

The version 1.0 of the PhytoCytoTraits application needs a recent version of R (version 4.3.x or upper). It is not available on the CRAN website.

The R-packages needed by PhytoCytoTraits application are: cluster, CytoDx, dbscan, dplyr, DT, flowcore, fpc, gdata, ggExtra, ggplot2, markdown, plotly, shiny, shinyalert, shinycssloaders, shinydashboard, shinyFiles, shinyjs, shinyWidgets and, V8.

CytoDx package can be download using BiocManager package. 

**Installation**

## Graphical User Interface

To launch the Graphical User Interface of PhytoCytoTraits, run these command lines in the R console:

*shinyApp(ui, server)*

![Graphical Use Interface](https://github.com/user-attachments/assets/e65b06ba-877d-407b-a27d-846eeccc40ab)

## General workflow

![Workflow PhytoCytoTraits](https://github.com/user-attachments/assets/568501fd-da34-4a9a-aa4a-a697b34839da)

## Funding

This programme has been developped by Arnaud Louchart and Dedmer Van de Waal in the frame of BloomTox project. BloomTox project has been funded by the European Union (ERC, BLOOMTOX, 101044452). Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or the European Research Council Executive Agency. Neither the European Union nor the granting authority can be held responsible for them.

The project has been conducted at the Netherlands Institute of Ecology of the Royal Netherlands Academy of Arts and Sciences (NIOO-KNAW) during Arnaud Louchart postdoc (2023-2026).

## References

- Attali D (2022). shinyjs: Easily Improve the User Experience of Your Shiny Apps in Seconds. R package version 2.1.0, https://deanattali.com/shinyjs/
- Attali D, Edwards T (2025). shinyalert: Easily Create Pretty Popup Messages (Modals) in 'Shiny'. R package version 3.1.0, , https://github.com/daattali/shinyalert.
- Chang W, Borges Ribeiro B (2025). shinydashboard: Create Dashboards with 'Shiny'. R package version 0.7.2, https://github.com/rstudio/shinydashboard.
- Chang W, Cheng J, Allaire J, Sievert C, Schloerke B, Xie Y, Allen J, McPherson J, Dipert A, Borges B (2025). shiny: Web Application Framework for R. R package version 1.10.0.9000, https://github.com/rstudio/shiny, https://shiny.posit.co/
- Ellis B, Haaland P, Hahne F, Le Meur N, Gopalakrishnan N, Spidlen J, Jiang M, Finak G (2024). flowCore: flowCore: Basic structures for flow cytometry data. R package version 2.18.0.
- Hahsler M, Piekenbrock M, Doran D (2019). “dbscan: Fast Density-Based Clustering with R.” Journal of Statistical Software, 91(1), 1–30. doi:10.18637/jss.v091.i01.
- Hennig C (2024). fpc: Flexible Procedures for Clustering. R package version 2.2-13, https://CRAN.R-project.org/package=fpc.
- Hu Z (2024). CytoDx: Robust prediction of clinical outcomes using cytometry data without cell gating. R package version 1.26.0.
- Ooms J (2025). V8: Embedded JavaScript and WebAssembly Engine for R. R package version 6.0.1, https://github.com/jeroen/v8.
- Perrier V, Meyer F, Granjon D (2025). shinyWidgets: Custom Inputs Widgets for Shiny. R package version 0.9.0, https://dreamrs.github.io/shinyWidgets/, https://github.com/dreamRs/shinyWidgets.
- Maechler M, Rousseeuw P, Struyf A, Hubert M, Hornik K (2024). cluster: Cluster Analysis Basics and Extensions. R package version 2.1.8 — For new features, see the 'NEWS' and the 'Changelog' file in the package source), https://CRAN.R-project.org/package=cluster.
- Sievert C (2020). Interactive Web-Based Data Visualization with R, plotly, and shiny. Chapman and Hall/CRC. ISBN 9781138331457, https://plotly-r.com.
- Wickham H, François R, Henry L, Müller K, Vaughan D (2023). dplyr: A Grammar of Data Manipulation. R package version 1.1.4, https://github.com/tidyverse/dplyr, https://dplyr.tidyverse.org.
- Wickham H (2016). ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York. ISBN 978-3-319-24277-4, https://ggplot2.tidyverse.org.
