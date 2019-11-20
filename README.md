This repository has a minimal working example of a R markdown template to create a UNC formatted dissertation. It is a slightly updated fork of [Ann Von Holle's template](https://github.com/avonholle/unc-dissertation-markdown-template). 

These files follow a successful submission of my formatted dissertation to the UNC Graduate School in 2018 and are according to graduate school standards [UNC graduate school standards](http://gradschool.unc.edu/academics/thesis-diss/guide/). 

## Requirements

1. R and [RStudio](https://rstudio.com/)
2. [MikTex](https://miktex.org/download)
3. [pandoc-eqnos](https://github.com/tomduck/pandoc-eqnos#installation) 
   * (which itself requires python)

# Steps to run the file in R Studio

1. Clone the repo to a local folder on your computer.
2. Open [dissertation.Rmd](dissertation.Rmd) in RStudio.
    * In the yaml header, make sure that your ```pandoc_args:``` section has the correct path to where pando-eqnos is installed. This will be different depending on your operating system and version of python installed.
    * Hit the 'Knit PDF' button in the window containing the dissertation.Rmd code.
    * You should get a [formatted PDF](dissertation.pdf) with the content in this template.
3. Modify the files to fit your content. 
   * Note: Try not to modify the .cls file unless you are LaTex literate. Even adding one extra package could throw the whole formatting scheme off.

