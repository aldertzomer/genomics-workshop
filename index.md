<p align="center">
  <img width="300" height="277" src="https://mmb-umcu.github.io/genomics-workshop/fig/logo.png" />
</p>

This course is a fork (copy) of the *Genomics Workshop* from [Data Carpentry](https://datacarpentry.org/) which is adjusted for the **Microbial Genomics course at Utrecht University**.
Data Carpentry’s aim is to teach researchers basic concepts, skills, and tools for working
with data so that they can get more done in less time, and with less pain. This workshop
teaches data management and analysis for genomics research including: 

- best practices for organization of bioinformatics projects and data, 
- use of command-line utilities, 
- use of command-line tools to analyze sequence quality and perform variant calling, 
- and connecting to and using cloud computing.  

  
## Getting Started

This lesson assumes that learners have no prior experience with the tools covered in the workshop.  
However, learners are expected to have some familiarity with biological concepts, including the concept of genomic variation within a population. Participants should bring their own laptops and plan to participate actively. 

## Data
 
This workshop uses data from a long term evolution experiment published in 2016: [Tempo and mode of genome evolution in a 50,000-generation experiment](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4988878/) by Tenaillon O, Barrick JE, Ribeck N, Deatherage DE, Blanchard JL, Dasgupta A, Wu GC, Wielgoss S, Cruveiller S, Médigue C, Schneider D, and Lenski RE. (doi: 10.1038/nature18959)  
  
All of the data used in this workshop can be [downloaded from Figshare](https://figshare.com/articles/Data_Carpentry_Genomics_beta_2_0/7726454). However to make things more convenient and limit the time to download large files, all data is provided locally in your cocalc personal home directory as well.  
More information about this data is available on the [Data page](https://aldertzomer.github.io/organization-genomics/data/).  

<br>

# Workshop Overview 

### Monday 11 Nov 2024 (day 1)

Room BOL-1.128 (morning) & BOL-1.138 (afternoon)  

| **Time&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**| **Lesson&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;** | **Overview** |
| :-- | :-- | :-- |
| 09:00-09:45 | Introduction to course | [ [**Michael Seidl**](https://www.uu.nl/staff/MFSeidl) ] |
| 09:45-10:15 | Introduction to data carpentry days 1-2 | [ [**Alex Bossers**](https://www.linkedin.com/in/alexbossers/) / [Tim Dallman](https://www.linkedin.com/in/timothy-dallman-a7535520/) / [Julian Paganini](https://www.linkedin.com/in/julian-paganini/) / [Aldert Zomer](https://www.linkedin.com/in/aldertzomer)] |
| 10:15-12:45 | [Introduction command line (1-4)](https://aldertzomer.github.io/shell-genomics/) <br> + code along |  **Students:** Learn to navigate your file system, create, copy, move, and remove files and directories, and automate repetitive tasks using scripts and wildcards. |
| 12:45-13:15 | Break | Move to other room! |
| 13:15-14:00 | [Introduction command line (5-6)](https://aldertzomer.github.io/shell-genomics/) | **Students:** Continue command line practicals or start Project organisation [Alex/Julian] |
| 14:00-14:30 | Sequence data formats and QC | [Alex/Julian] |
| 14:30-16:00 | [Project organization and management](https://aldertzomer.github.io/organization-genomics/) | **Students:** Learn how to structure your metadata, organize and document your genomics data and bioinformatics workflow, and access data on the NCBI sequence read archive (SRA) database.|
| 16:15-17:00 | Self study | **Students** |


### Tuesday 12 Nov 2024 (day 2)

Room BOL-1.138 (morning) & BOL-1.075 (afternoon)  

| **Time&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**| **Lesson** | **Overview** |
| :-- | :-- | :-- |
| 09:00-09:15 | Checkin and recap day 1 | [Alex/Julian] |
| 09:15-10:00 | Introduction to LTEE | [**Julian**] |
| 10:00-12:45 | [Data wrangling and processing](https://aldertzomer.github.io/wrangling-genomics/) | **Students:** Use command-line tools to perform quality control, align reads to a reference genome, and identify and visualize between-sample variation. |
| 12:45-13:15 | Break | Move to other room! |
| 13:15-13:45 | WGS to MGS | [Alex] |
| 13:45-15:45 | [Data wrangling and processing](https://aldertzomer.github.io/wrangling-genomics/) | **Students:** Continue to the finish |
| 15:45-16:00 | Plenary status check, problems/difficulties to address? | All |
| 16:15-17:00 | Self study | **Students** |
  
 
<br>
<br>

🔴 **<span style="color: red;">If all of the above is peanuts</span>, move ahead and master your skills with the optional extra's shown below!**<br>

<br>

# **Optional** Additional Lessons (Extra self-study)

| Lesson | Overview |
| :-- | :-- |
| [Bash scripting exercises: grep](https://ryanstutorials.net/linuxtutorial/grep.php) | Learn grep and **regular expressions** with examples 
| [Bash scripting exercises: sed](https://www.tutorialspoint.com/sed/) | sed tutorial for advanced learners
| [Bash scripting exercises: awk](https://www.tutorialspoint.com/awk/) | awk tutorial with many examples 
| [Putting your grep/sed/awk knowledge to the test](https://www.hackerrank.com/domains/shell?filters%5Bsubdomains%5D%5B%5D=grep-sed-awk) | Challenges for grep/sed/awk programmers. Requires a user account at [hackerrank](http://www.hackerrank.com)
| [Intro to R and RStudio for Genomics](https://datacarpentry.org/genomics-r-intro/) | Use R to analyze and visualize between-sample variation. Please note that workshop materials for working with Genomics data in R are in “alpha” development. In these lessons they instruct to do a local install or go to Amazon for Rstudio. Alternative you can use a FREE instance in the cloud at https://rstudio.cloud/ (preferred option) |
| [R for reproducible scientific analyses](https://swcarpentry.github.io/r-novice-gapminder/) | Fundamentals in R and tidyverse |
| [Genomics in the cloud (AWS)](https://datacarpentry.org/cloud-genomics/) | Learn how to work with Amazon AWS cloud computing and how to transfer data between your local computer and cloud resources ([setting-up own cloud instance instructions](https://datacarpentry.org/genomics-workshop/AMI-setup)). *Only necessary when you want to run your own instance of this course on an AWS instance!*

# Teaching Platform
This workshop is as original as possible from the [Data Carpentries workshop series](http://datacarpentry.org/) however it was partly redesigned to initially be run at the CoCalc platform hosted at Utrecht University, but **from edition 2024** onwards we moved back to a classical (full) command line interface at **[gemini.science.uu.nl](ssh://gemini.science.uu.nl)**!<br>
If you want to run your own instance of a similar server used for this workshop, follow the directions to generate an Amazon version as described on [DataCarpentry genomics](https://datacarpentry.org/genomics-workshop/AMI-setup) or alternatively try the *Windows Subsystem for Linux* (WSL Ubuntu) on MS windows.  
