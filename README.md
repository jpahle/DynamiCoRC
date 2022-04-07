[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6423078.svg)](https://doi.org/10.5281/zenodo.6423078)

# Dynamic Publication Media with the COPASI R Connector (CoRC) 

Dynamically published documents (instead of static ones like books and papers) offer a wide range of advantages.
They are created dynamically, using code (chunks), and/or you can interact with them. 

Here, we focus on three different main application areas for dynamic documents: **Documentation**, **Teaching** and **Science Communication**.
With this repository, we publish a selection of example documents illustrating the use of dynamic documents covering these topics:

- Documentation
  - Optimisation  
    [[HTML page](https://jpahle.github.io/DynamiCoRC/optimisation)] [[Source code](optimisation.Rmd)]
  - Parallel Processing  
    [[HTML page](https://jpahle.github.io/DynamiCoRC/parallel)] [[Source code](parallel.Rmd)]
- Teaching
  - Michaelis-Menten Kinetics  
    [[HTML page](https://jpahle.github.io/DynamiCoRC/michaelismenten)] [[Source code](michaelismenten.Rmd)]
  - Parameter Estimation  
    [[HTML page](https://jpahle.github.io/DynamiCoRC/parameterestimation)] [[Source code](parameterestimation.Rmd)]  
    [[Shiny app](https://lab.pahle.org/DynamiCoRC/parameterestimation)] [[Source code](shinyapps/parameterestimation/parameterestimation.Rmd)]
  - Oscillatory Dynamics  
    [[HTML page](https://jpahle.github.io/DynamiCoRC/oscillations)] [[Source code](oscillations.Rmd)]  
    [[Google Colab](https://lab.pahle.org/DynamiCoRC/oscillatorydynamics)] [[Source code](oscillations.ipynb)]
- Science Communication
  - Infection Dynamics  
    [[Shiny app](https://lab.pahle.org/DynamiCoRC/infectiondynamics)] [[Source code](shinyapps/infectiondynamics/infectiondynamics.Rmd)]

# Dynamic Documents with CoRC

**CoRC** is a high-level API of COPASI in the (statistical) programming environment **R** (for more information look at the [CoRC](https://jpahle.github.io/DynamiCoRC/corc.html) tab).
The combination of CoRC with dynamic documents allows for easy interaction with complex (biological) models, both in the creation and handling.
Newcomers and advanced creators alike can benefit from displaying code with dynamic documents.

# Dynamic Document Creation

Most of the files here are created using [R Markdown](https://rmarkdown.rstudio.com/).
It is a markdown language that is easy to use and can be very powerful in combination with for example [shiny applications](https://shiny.rstudio.com/) or [flexdashboards](https://rmarkdown.rstudio.com/flexdashboard/).

We also provide one document based on Jupyter. Jupyter notebooks are another popular form of dynamic documents with many similar capabilities but some differences in structure.

# Dynamic Hosting options

There are a lot of hosting options for dynamic documents.
Most of the files created and used here are hosted on [Github Pages](https://pages.github.com/).
While very easy to use, all the websites hosted there are static.

In addition, one document in Jupyter notebook format is hosted on [Google Colab](https://colab.research.google.com).
Here, it is possible to code online, within the document.

The more interactive R Markdown documents, like shiny apps and flexdashboards are hosted on [shinyapps.io](https://www.shinyapps.io/).

# Authors

Johanna Daas, Jonas D. Förster and Jürgen Pahle.

# Licence

All the material here is published under the [Creative Commons BY 4.0 licence](https://creativecommons.org/licenses/by/4.0/legalcode.txt).
