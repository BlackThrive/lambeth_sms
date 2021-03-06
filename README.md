<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="images/btg_logo.png" alt="Logo" width="140" height="140">
  </a>
  </div>
  
# Black Thrive Shared Measurement System for Lambeth
 
## Overview

This Rproject contains the scripts and data necessary to produce the methods, procedure, and results for Black Thrive's Shared Measurement System analysis for Lambeth. 

The aim of this analysis is to quantify racial inequality in Lambeth by comparing various indicators for the Black population with the White population. Doing so makes it possible to identify the aspects of life in Lambeth where inequality is manifest and to highlight where change is needed.

## Requirements

### Programs

RStudio is required to open and run the analysis. This project was produced using 

- RStudio 2021.09.0 Build 351 "Ghost Orchid"
- R version 4.1.1

### Packages required

The script uses the following R packages. These need to be installed using <b>install.packages("</b>package name<b>")</b> if they are not already installed on your system.

- gmodels
- tidyverse
- ggrepel
- kableExtra
- epitools
- scales
- showtext

## Contents

**lambeth_sms.Rproj**: Project file.

### Data

**data/Stops_LDS_Extract_12MonthsToEnd_202109.zip**: Stop and Search data for Lambeth. csv file within eeds to be unzipped to data folder

**data/lambeth_cla_2019.csv**: Data for Children Looked After indicator

**data/lambeth_employment_rate_march_2021_v2.csv**: Employment rate data

**data/lambeth_gcse_2019_2020.csv**: Data for number of pupils achieving at least Level 4 in GCSE English and Maths

**data/lambeth_gld_2018_2019.csv**: Data for number of children reaching a Good Level of Development at age 5.

**data/lambeth_population.csv**: Data for population estimates

**data/lambeth_stat_homeless_jun_2021.csv**: Data for number of households statutorily homeless or at risk of becoming homeless

### Scripts

**scripts/lambeth_sms_analysis.Rmd**: Script for processing and analysing data.

**scripts/lambeth_sms_analysis.html**: Knitted html markdown file generated by above script.

### Other

**images/btg_logo.png**: Black Thrive logo

## Setup

Once downloaded, unzip to a destination of your choice. Note that the Stop and Search data also needs to be unzipped, with the resulting csv file being located in the ***data*** directory. Be sure to retain the original folder structure.

Use **lambeth_sms.Rproj** to open project. 

To load the analysis script, use *File > Open File*, navigate to the ***scripts*** folder, and select **lambeth_sms_analysis.Rmd**. To run the script, select *Run > Run all* (Ctrl + Alt + R [Windows]; Cmd + Option + R[Mac]).

If you just want to view the knitted html document, using your system file navigator navigate to the scripts folder and open **lambeth_sms_analysis.html** in your preferred browser.



## Contact

If you have any questions, comments, or feedback please contact the Research Team at Black Thrive: research@blackthrive.org, FAO Jolyon Miles-Wilson.
