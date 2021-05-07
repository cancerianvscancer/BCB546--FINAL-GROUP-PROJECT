# BCB546X-Animal Crossers-Final project
Repository to share files, edit and analyze data for final group project by 'Animal Crossers'
Group members: Giang Nguyen, Prita Pandya, Sushma Ambekar and Vishesh Bhatia

This project was based on the paper **'Genome-wide analysis of multi- and extensively drug-resistant Mycobacterium tuberculosis'**. 
This article can be found [here](https://www.nature.com/articles/s41588-017-0029-0)

## Description of the repository

### Home directory
The home directory contains the [PDF](https://github.com/cancerianvscancer/BCB546--FINAL-GROUP-PROJECT/blob/main/Coll_etal-2018.pdf) of the paper we worked on, the [slides](https://github.com/cancerianvscancer/BCB546--FINAL-GROUP-PROJECT/blob/main/Final%20project-%20Animal%20crosssers.pdf) presented in the class as well as the sub-directories listed below. [Coll_etal-2018](https://github.com/cancerianvscancer/BCB546--FINAL-GROUP-PROJECT/blob/main/Coll_etal-2018.md) gives a brief description of the paper, the analyses conducted and results obtained.

### 1. Raw data
All data obtained from the paper used for our analysis can be found in the `Raw data` directory. Table 1, 2 and 3 were available as .xlsx files while supplementary tables were processed from PDF format using Virtual Studio Code to generate .xlsx files.

### 2. Graphs generated
All graphs were generated with R Studio Version 1.4.1106 using the ggplot package. Data required for generating the graphs can be found in the `Raw data` directory and will have to be downloaded prior to use.

### 3. Code
Scripts for the plots were written and commented in R markdown and are available in this directory. Each .Rmd file is named based on the figure it is used for, from the paper.

## Contributions to the project
The paper to be replicated was chosen from multiple other options by the group. We attempted to reach out to the authors and request for missing data but they were unresponsive.

- First the repository was created by Prita Pandya to help share the data and work together. Each member of the group was added and give them administrator access. 
- Raw data was processed as excel sheets and uploaded to the Github repository by Giang Nguyen.
- Plots generated for Fig1 showing the geographic distribution of the lineages and drug resistant phenotypes was done by Sushma Ambekar. For this, the data was first plotted as a bar graph and then converted to a pie chart using the function coord_polar(). Latitudes and longitudes of the geographical locations were obtained and the pie charts were plotted on the world map using scatterpie.
- Coll_etal-2018.md file was worked on by Vishesh Bhatia and Sushma Ambekar giving a brief description of the paper.
- The data in Table 1 and Table 2 given in the paper was used to make graphs using R by Prita Pandya. We wanted to represnt the table data visually thorugh graphs.
- For the figures 3a and 3b, Gian Nguyen randomly selected genes from the figure 3 in the paper and created excel file with make up numbers/ data due to unavailibility of the actual data. 
- Using the make up file provided with the files in the repository, Giang Nguen made the figures 3a and 3b using R
- Supplementary Table 4 was processed as excel sheet and for every gene present in the particular lineage, a score of 1 was given. The total hits were counted and presented in Figure_4. The code of for the figure can be found in the Code Folder and the figure is in the Graphs Generated Folder. All of this was performed by Vishesh Bhatia. 
- Slides for the presentation were made by contribution from all team members.
