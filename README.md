# NTNU Workshop

***

# Preparations:

## Step 1:

Large repository preparations: 

- Typically a project will have a single script containing all of the code (e.g., `.R` or `.Rmd`)
- Due to the number of scripts in this repository we will change the starting file-path at the beginning of each exercise to the folder associated with that script.
- To make this work each course participant must manually copy the file-path of their project folder location into the file named `rep_functions.R`. 


`project_location <- "/your/unique/file-path-stem/NTNU-start"` 


- This can easily be done by loading the `here` package, running `here()`, and copying the path. 
- This procedure is unique to this large repository structure & will generally not be a necessary step.

***

## Step 2

Install and load packages. See end of the script named `01-intro.Rmd` for full list of packages.