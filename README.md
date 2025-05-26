# ENVS193DS-Homework03
Assignment/Homework 03 for Data Science in Environmental Studies (ENVS 193DS)

### General Information 

#### Personal Data Exploration
An aspect of this R project is that it explores the relationship between workout intensity, body part trained, and water consumption using personal observational data collected over several weeks. The final visualization is a digitally illustrated figure that maps hydration and effort directly onto muscle groups, combining data-driven insights with creative representation. Statistical summaries were created in R, and visual elements were designed to make the data more intuitive, engaging, and personally meaningful. The project is inspired by affective data visualization principles and integrates both analytical and artistic approaches. 

#### Paper Critique Summary
As part of this project, I reviewed Jasechko & Perrone (2021) (DOI: 10.1126/science.abc2755), which explores whether groundwater wells are being constructed deeper over time in response to declining water tables. The authors used Spearman’s rank correlation to examine well depth trends and presented their findings through multi-layered figures. While the statistical representation was effective, I recommended improvements such as increasing x-axis spacing to reduce point overlap, separating the spatial distribution panel into its own figure, and adjusting plot bounds to avoid clipping points at the visual margins. 


### Packages 

Make sure you have these installed before running the code!

```

library(tidyverse) # general use 

library(gt) # for summary table

library(janitor) # cleaning data frames 

library(here) # file organization 

library(readxl) # reading excel files 

library(dplyr) # enables dataframe manipulation in an intuitive, user-friendly way

library(fs) # allows you to make a tree of the data structure

```

### Data and File Information

├── ENVS193DS-Homework03.Rproj
├── README.md
├── code 
│   ├── Affective_Data.jpg
│   ├── ENVS-193DS_homework-03.html
│   ├── ENVS-193DS_homework-03.qmd
│   ├── ENVS-193DS_homework-03_files
│   │   ├── figure-html
│   │   │   └── Personal Data Visualization-1.png
│   │   └── libs
│   │       ├── bootstrap
│   │       │   ├── bootstrap-icons.css
│   │       │   ├── bootstrap-icons.woff
│   │       │   ├── bootstrap.min.css
│   │       │   └── bootstrap.min.js
│   │       ├── clipboard
│   │       │   └── clipboard.min.js
│   │       └── quarto-html
│   │           ├── anchor.min.js
│   │           ├── popper.min.js
│   │           ├── quarto-syntax-highlighting.css
│   │           ├── quarto.js
│   │           ├── tippy.css
│   │           └── tippy.umd.min.js
│   └── StatisticalCritiqueFigure.jpg
└── data
    └── PersonalStudyHome.csv


### Rendered Output 

The rendered output is [here](URL goes here).

