# R Notes 

---
## Updating R
In base R you can use the `installr` package. Then just run `updateR()`. There are steps to ask about copying over packages and settings. 

---
## Running R from the command line 

To simply run what's in a `.R` script and output results to `cmd`, use 
`Rscript test.R`

---
# RMarkdown notes

- see `Example.Rmd`

## Rendering from base R

- need `rmarkdown` package
- then call `rmarkdown::render("Example.Rmd", output_dir = "../output")`

- one annoying thing is that this doesn't use whatever information the "knit" button is doing in Rstudio. So need to specify output directory here if you want it to be different from where the code resides. 