Last update 12/02/2023
# Welcome!

## About this repository

### Authors
* Astrid Sanna (leader), astrid87@uw.edu.
* Jimmy Fowler (assistant), jfowler0@uw.edu.

### Branches
There are 3 branches: main, Astrid, and Jimmy. Most of the work was done on Astrid and Jimmy branches. 
The main branch includes the final, polished work. This README file describes what you will find in the main branch. 

### Material included 
* A report in the form of a notebook where our project is fully described. The entire code is also available here.
* All figures produced by running the code in the notebook.
* Presentation slides that briefly describe our project.
* Metadata document describing all the variables used in this analysis, and including maps of the study area. 

### Purpose 
* to have an online, collaborative space to work on our ML project
* to document and encourage reproducible science
* to showcase skills learned in [MLGeo-2023](https://github.com/UW-ESS-DS/MLGeo-2023)

### Cloning
Cloning a repository is easy! See example below to clone this one. 
```
PS C:\Users\astri> cd "G:\My Drive\MASTER\Classes\ESS_569_ML\GitHub_repositories"
PS G:\My Drive\MASTER\Classes\ESS_569_ML\GitHub_repositories> git clone https://github.com/UW-ESS-DS/MLGeo2023_ESS569_AstridSanna.git
```
### Why we chose the MIT Licence 
The MIT License is a clear and accommodating open-source license, permitting free use, alteration, and sharing of software, and it 
requires giving credit to the original creator; this has led to its broad acceptance and has removed obstacles for its adoption.

## Favorite Earth Science topics
* Forest and fire ecology
* Climate change
* Conservation and Biodiversity
 
## Our Project 

**All data considered for building the data frame that was used for this project is stored on [Google Drive](https://drive.google.com/drive/folders/11NSQJsinT8awAIQW_oEajdHkONbcQsUZ?usp=sharing) with limited access. CSVs files are available at ESS_569_ML_project/Data/CSVs.**

### Background 
Forest fires are a growing concern, with their frequency and severity increasing in recent decades. 
The Bootleg Fire in Oregon, which burned over 400,000 acres of forestland in 2021, provides an opportunity 
to explore the role of fuel treatments in mitigating fire severity and evaluate the importance of 
environmental variables as drivers of burn severity. The major categories of variables that will be 
explored include: climate, fire weather, topography, fuel treatments, and forest structure. 
While all categories have some importance in explaining burn-severity variability, only fuel treatments 
and forest structure are under our control, to some extent. Despite the extensive literature documenting 
the mitigating effects of fuel treatments on burn severity, the complex and dynamic nature of wildfires 
presents significant interpretive challenges. Identifying site-specific, key drivers of burn severity and 
the role of fuel treatments in mitigating burn severity are crucial tasks. Such insights guide the strategic 
allocation of limited management resources and lay the groundwork for future research. 

### Research question
Which environmental variables drove burn severity and what was the role of fuel treatments in mitigating burn severity?
#### Objective: 
Quantifying the global and local importance of burn severity drivers.

### Datasets 
Fuel-treatments, environmental variables, satellite-derived burn severity index (relativized burn ratio - RBR), LiDAR forest metrics. 
The original data format was eaither raster or shapefile. All varibales were transformed into rasters and values were extracted and compiled in a 
single .csv file. A metadata document is included in this repository and will help the reader to understand each variable used in this anlysis. 
The metadata document also includes maps of the study area. **The data used for this project cannot be openly distributed at this time** since 
Astrid’s manuscript has not been published yet. The data can be accessed *exclusively* for the purpose of this assignment 
by Jimmy Flowler, Marine Denolle, and Akshay Mehra. However, the report notebook, metadata, presentation slides, and figures are publicly 
published on this GitHub repository and can be downloaded by anyone. 

### Methods 
Check out our Burn_severity_notebook.ipynb! 

### Contact information / getting help: 
astrid87@uw.edu


