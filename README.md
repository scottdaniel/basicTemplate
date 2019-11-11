# basicTemplate

The most basic bioinformatics R markdown template.

This project was created by following this [guide](https://rstudio.github.io/rstudio-extensions/rmarkdown_templates.html) from the friendly folks at Rstudio Inc.

Uses the setup paradigm of "mother" and "child" reports as detailed in this [blog post](https://martinctc.github.io/blog/first-world-problems-very-long-rmarkdown-documents/)


## Install
```
if (!requireNamespace("devtools")) install.packages("devtools")
devtools::install_github(repo = "scottdaniel/basicTemplate")
```
## Usage
Once installed, you can create a new R markdown file from within Rstudio, just go to New File... > R markdown... > From Template and then select your template as the option and click [OK]

## Modifying
I selected my most commonly used packages as well as some "common_functions" that I used often in my reports. To customize this, just fork the repo, create a new project inside the directory, and then modify the files inside `/inst/rmarkdown/templates/boilerplate/skeleton`.

After you're done, just `Install and Restart` under the Build tab. Of course, if you find any bugs / add new features / embetter the code; feel free to create a pull request :)

## In the works...
Rstudio project template that uses this Rmarkdown template
