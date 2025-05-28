# ENVS193DS-Homework03
Spring Quarter, 2025
Assignment/Homework 03 for Data Science in Environmental Studies (ENVS 193DS)

### General Information 

The dataset is from a personal study that I have been conducting over the span of the Spring 2025 quarter. I was interested in the amount of water I drank depending on the type and length of workout. 

The published paper is: Jasechko, S., Perrone, D. (2021). Global groundwater wells at risk of running dry. *Science*, 372(6540), 418-421. 10.1126/science.abc2755. 


#### Personal Data Exploration
Aa part of this R project is that it explores the relationship between workout intensity, body parts trained, and water consumption using personal observational data collected over several weeks. The final visualization is a digitally illustrated figure that maps hydration and effort directly onto muscle groups, combining data-driven insights with creative representation. Statistical summaries were created in R, and visual elements were designed to make the data more intuitive and personally meaningful. The project is inspired by affective data visualization principles and integrates both analytical and artistic approaches. 

#### Paper Critique Summary
As part of this project, I reviewed *Global groundwater wells at risk of running dry*, written by Scott Jasechko & Debra Perrone (2021) (DOI: 10.1126/science.abc2755), which explores whether groundwater wells are being constructed deeper over time in response to declining water tables. The authors used Spearman’s rank correlation to examine well depth trends and presented their findings through multi-layered figures. While the statistical representation was effective, I recommended minor but important improvements to elevate the figures dimensionality. 


### Packages 

Make sure you have these installed before running the code!

```

library(tidyverse) # general use 

library(gt) # for summary table

library(janitor) # cleaning data frames 

library(here) # file organization 

library(readxl) # reading excel files 

library(dplyr) # enables dataframe manipulation

library(fs) # allows you to make a tree of the data structure

```

### Data and File Information

File Structure: 
```

├── ENVS193DS-Homework03.Rproj
├── README.md
├── code                                        # code folder 
│   ├── Affective_Data.jpg                       
│   ├── Draftdata.jpg                            
│   ├── ENVS-193DS_homework-03.html             # rendered output 
│   ├── ENVS-193DS_homework-03.qmd               
│   ├── ENVS-193DS_homework-03_files
│   │   ├── figure-html
│   │   │   └── Personal Data Visualization-1.png
│   │   └── libs
│   │       ├── clipboard
│   │       └── quarto-html
│   │       
│   └── StatisticalCritiqueFigure.jpg
└── data                                        # data folder 
    └── PersonalStudyHome.csv
    
```
All the code is in the code folder. 

### Rendered Output 

The rendered output is [here](https://ethan-mathews24.github.io/ENVS-193DS_homework-03/code/ENVS-193DS_homework-03.html).

