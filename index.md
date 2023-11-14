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

### Monday 13 Nov (day 1)

Room BOL-1.128 & Ruppert-134  

| **Time&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**| **Lesson&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;** | **Overview** |
| :-- | :-- | :-- |
| 09:00-09:45 | Introduction to course | [ [**Michael Seidl**](https://www.uu.nl/staff/MFSeidl) ] |
| 10:00-10:45 | Introduction to data carpentry days 1-3 | [ [**Alex Bossers**](https://www.linkedin.com/in/alexbossers/) / [Tim Dallman](https://www.linkedin.com/in/timothy-dallman-a7535520/) / [Julian Paganini](https://www.linkedin.com/in/julian-paganini-bb6328104/) / [Aldert Zomer](https://www.linkedin.com/in/aldertzomer)] |
| 11:00-12:30 | [Project organization and management](https://aldertzomer.github.io/organization-genomics/) | Learn how to structure your metadata, organize and document your genomics data and bioinformatics workflow, and access data on the NCBI sequence read archive (SRA) database.|
| 12:30-13:00 | Break | Move to other building! |
| 13:15-14:00 | Introduction to LTEE | [**Julian**] |
| 14:15-16:00 | [Introduction command line (1-3)](https://aldertzomer.github.io/shell-genomics/)  +discussion |  Learn to navigate your file system, create, copy, move, and remove files and directories, and automate repetitive tasks using scripts and wildcards. |

### Tuesday 14 Nov (day 2)

Room Ruppert-116 & BBG-165  

| **Time&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**| **Lesson** | **Overview** |
| :-- | :-- | :-- |
| 09:00-09:45 | Introduction research (NGS, quality, variant calling towards phylogenomics) | [**Tim**] |
| 10:00-12:15 | [Introduction command line (4-6)](https://aldertzomer.github.io/shell-genomics/) | Recap Day 1<br>Continue from Day 1 or start data wrangling<br>Sequence data formats + fastQC [ALex/Julian] |
| 12:15-13:00 | Break |
| 13:15-15:45 | [Data wrangling and processing](https://aldertzomer.github.io/wrangling-genomics/) | [**Alex/Julian**] Check-in<br>Discussion getting the max from FastQC<br><br>[**Students**] Use command-line tools to perform quality control, align reads to a reference genome, and identify and visualize between-sample variation. |
| 15:45-16:00 | Plenary status check, problems/difficulties to address? | All |
  
### Wednesday 15 Nov (day 3)

Room Ruppert C & BOL-1.128  

| **Time&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**| **Lesson&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;** | **Overview** |
| :-- | :-- | :-- |
| 09:00-09:45 | Introduction to Metagenomics and Metabarcoding) | [**Alex**] |
| 10:00-12:00 | [Data wrangling and processing](https://aldertzomer.github.io/wrangling-genomics/) +discussion | Continue from Day 2 |
| 12:15-13:00 | Break |
| 13:00-13:45 | Introduction to phylogenetic methods  | [**Tim**] |
| 14:00-14:15 | Check-in / status / discussion points | All |
| 14:15-16:00 | [Data wrangling and processing](https://aldertzomer.github.io/wrangling-genomics/) | All - Finishing up |
| 15:00- | Wrapping-up / status<br>+ self study extra's [Introduction to cloud computing for genomics](http://aldertzomer.github.io/cloud-genomics/) | Optional - Learn how to work with Amazon AWS cloud computing and how to transfer data between your local computer and cloud resources. *Only necessary when you want to run your own instance of this course on an AWS instance.*<br><br>Not included in the exam.| 
  
<br>

# **Optional** Additional Lessons (Extra & Wednesday self-study)

| Lesson | Overview |
| :-- | :-- |
| [Bash scripting exercises: grep](https://ryanstutorials.net/linuxtutorial/grep.php) | Learn grep and **regular expressions** with examples 
| [Bash scripting exercises: sed](https://www.tutorialspoint.com/sed/) | sed tutorial for advanced learners
| [Bash scripting exercises: awk](https://www.tutorialspoint.com/awk/) | awk tutorial with many examples 
| [Putting your grep/sed/awk knowledge to the test](https://www.hackerrank.com/domains/shell?filters%5Bsubdomains%5D%5B%5D=grep-sed-awk) | Challenges for grep/sed/awk programmers. Requires a user account at [hackerrank](http://www.hackerrank.com)
| [Intro to R and RStudio for Genomics](https://datacarpentry.org/genomics-r-intro/) | Use R to analyze and visualize between-sample variation. Please note that workshop materials for working with Genomics data in R are in “alpha” development. In these lessons they instruct to do a local install or go to Amazon for Rstudio. Alternative you can use a FREE instance in the cloud at https://rstudio.cloud/ (preferred option) |
| [R for reproducible scientific analyses](https://swcarpentry.github.io/r-novice-gapminder/) | Fundamentals in R and tidyverse |

# Teaching Platform
This workshop is as original as possible from the [Data Carpentries workshop series](http://datacarpentry.org/) however it was partly redesigned to be run on the [Cocalc instance (3)](https://cocalc3.science.uu.nl/) or [Cocalc instance (4)](https://cocalc4.science.uu.nl/) platform hosted at Utrecht University.
If you want to run your own instance of a similar server used for this workshop, follow the directions in the [Setup](setup.html) tab to generate an Amazon version (without the cocalc interface) or go to the http://datacarpentry.org/ website for more information.  
