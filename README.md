# Accessing RStudio 

Below are options to access RStudio at Duke. 

:one: [RStudio Docker container](https://vm-manage.oit.duke.edu/containers) managed by Duke OIT VM-Manage: As a Duke student, you have access to RStudio through a Docker container managed by Duke OIT. Use your NetID to reserve a generic **RStudio** container. It is already set up to utilize version control using Git. [Click here](https://github.com/DukeStatSci/github_auth_guide) for instructions on configuring GitHub authentication. 

:two: **Install RStudio on your laptop**: You can install RStudio on your local machine and configure it to work with Git and GitHub. The text [Happy Git and GitHub for the useR](https://happygitwithr.com/) is a great resource to help you install RStudio and configure Git. Here is a basic outline of the steps:

- [Install or Upgrade R and RStudio](https://happygitwithr.com/install-r-rstudio.html)
- [Install Git](https://happygitwithr.com/install-git.html)
- [Introduce Yourself to Git](https://happygitwithr.com/hello-git.html)
Connect RStudio to Git and GitHub
- [Configure GitHub authentication](https://github.com/DukeStatSci/github_auth_guide)
- If you want to use R Markdown to produce PDF documents, install the [**TinyTex**](https://yihui.org/tinytex/) R package by running the following code in the console: 

```r
install.packages('tinytex')
tinytex::install_tinytex()
```
