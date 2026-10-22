# EDS 223 HW 1: Traffic Proximity, PM2.5, and Income on LA County

## Purpose
This repo is used for the first homework assignment of EDS 223, Geospatial Analysis and Remote Sensing. The course introduces the spatial modeling and analytic techniques of geographic information science to data science students. The emphasis is on deep understanding of spatial data models and the analytic operations they enable. Recognizing remotely sensed data as a key data type within environmental data science, this course will also introduce fundamental concepts and applications of remote sensing. For this assignment specifically, I will explore an environmental justice topic of my choosing. The data comes from the United States Environmental Protection Agency’s previous EJScreen: Environmental Justice Screening and Mapping Tool. 


## Repository Organization
```
eds223-hw1
│   README.md           # Overview of the repository
│   HW2.qmd
│   Rmd/Proj files    
│
└───.gitignore
     └───data
         └───ejscreen
         └───SWITRS_LA
         └───mapping-inequality
```

## Data Access
The data comes from the U.S. EPA's EJScreen (2023, Version 2.2) at the census block group level. Because the files are too large for GitHub, the `data/` folder is listed in `.gitignore`. To run the analysis, download the data from [(https://drive.google.com/file/d/1nG6Nj1bXfzQFOVMO8Km3eNy4SWu1YcIQ/view?usp=sharing)], unzip it, and place the files in a `data/` folder at the root of this repository.

## Author
Kailani Latimer ([https://github.com/kailani-boop])

## References
- EDS 223 Homework 1 instructions: ([https://eds-223-geospatial.github.io/assignments/HW1.html])
- U.S. Environmental Protection Agency. (2023). *EJScreen: Environmental Justice Screening and Mapping Tool* (Version 2.2). [(https://pedp-ejscreen.azurewebsites.net/)]
- U.S. Environmental Protection Agency. (2023). *EJScreen Technical Documentation, Version 2.2.*
