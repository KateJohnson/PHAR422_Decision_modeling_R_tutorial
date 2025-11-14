# PHAR422 Decision modeling in R tutorial (Fall 2024)

## Learning Objectives
- Construct a cohort-based Markov model in R
- Determine the ICER and display results on a cost-effectiveness plane
- Develop a probabilistic sensitivity analysis
- Characterize parameter uncertainty using a cost effectiveness acceptability curves


## 1. Installation

We will be working on local installations of *R* and *RStudio*. If you do not already have them installed on your computer, follow these instructions:

### 1a. Install R
- Go to [CRAN](https://cran.r-project.org/).
- Download the installer for your operating system.
- Run the installer and accept the default options unless your course specifies otherwise.

### 1b. Install RStudio
- After installing R, download [RStudio Desktop](https://posit.co/download/rstudio-desktop/).
- Choose the correct installer for your OS.
- Complete the installation using the default settings.

---

**Note:** For more detailed instructions, visit the [UBC MDS installation guide](https://ubc-mds.github.io/resources_pages/installation_instructions/).  
Select your OS and then review the sections for **R**, **XQuartz**, **IRkernel**, and **RStudio**.  
You only need the first paragraph of instructions for each.

---

**Please have R and RStudio installed before the start of class.**

## 2. Download a local version of this repository

- Go to https://github.com/KateJohnson/PHAR422_Decision_modeling_R_tutorial
- Under the green 'code' button (top right), 'download ZIP' to download a local copy of the entire repository and its contexts
![ ](Figures/download_zip.PNG)
- Unzip and open the repository from your downloads folder
- Click to open the `PHAR22_Decision_modeling_R_tutorial.Rproj` folder (in RStudio, if asked)
- We will work on `markov_model_tutorial.qmd`

*Note: you may want to move the R project folder out of your downloads folder to a more logical place, such as where you store 
class materials on your computer. You can do that within finder by dragging and dropping the entire folder to your preferred location.
