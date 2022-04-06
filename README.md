---
Title: "Readme"
Author: "Fredata"
Date: '2022-03-28'
Output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)

```
## Case Study: How Does a Bike-Share Navigate Speedy Success?
### Introduction
#### Cyclistic bike-share analysis case study!

As a young data analyst, I do several real-world duties in this case study. I work for a fictitious corporation, and I use the phases of the data analysis process to address crucial business questions: ask, prepare, process, analyze, share, and act. I will have a portfolio-ready case study at the end of this case study.

### Report deliverables:

#### Case Study Roadmap -Ask

##### Deliverables
A clear statement of the business task : 
###### To enhance the number of yearly memberships by analyzing past travel data
Consider Stakeholders: 
###### Director of marketing has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics.

#### Case Study Roadmap -Prepare
##### Deliverables
A description of all data sources used
##### DATA Source & license 
The data has been made available by Motivate International Inc. under this license: <https://ride.divvybikes.com/data-license-agreement>
The data is well organized, sperated into two different sets as below:
##### 1- Station Data ( till 2016)

###### -- Sample Data Summary ------------------------
                           Values     
Name                       stationdata
Number of rows             300        
Number of columns          7          
_______________________               
Column type frequency:                
  character                2          
  numeric                  5          
________________________              
Group variables            None 

##### 2- Trip data (till 02/2022)

###### -- Sample Data Summary ------------------------
                           Values  
Name                       tripdata
Number of rows             759788  
Number of columns          12      
_______________________            
Column type frequency:             
  character                4       
  numeric                  6       
  POSIXct                  2       
________________________           
Group variables            None  

###### I downloaded all of the files from the server for the project and organized them into multiple folders, taking into account the consistency of the data and how it is updated. They are now ready for the process phase.

#### Case Study Roadmap -Process
##### Deliverables
Documentation of any cleaning or manipulation of data
###### Pre Start: 
For the process stage, I'd prefer load the files in Rstudio and do a clean / check process before adding additional columns for further analysis. After combining them into a single file, I examine the file size before proceeding.
1) Open Rstudio
2) Set the new directory: setwd("G:/01 Case Study/CASE01/Files/02 Trips")
3) 



#### Case Study Roadmap -Analyze

##### Deliverables
A summary of analysis

#### Case Study Roadmap -Share

##### Deliverables
Supporting visualizations and key findings

#### Case Study Roadmap -Act

##### Deliverables
Your top three recommendations based on analysis

##### R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.
