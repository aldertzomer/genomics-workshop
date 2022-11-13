<p align="center">
  <img width="300" height="277" src="https://mmb-umcu.github.io/genomics-workshop/fig/logo.png" />
</p>

This course is a copy of the Genomics Workshop from Data Carpentry which is adjusted for the **Microbial Genomics course at Utrecht University**.
Data Carpentry’s aim is to teach researchers basic concepts, skills, and tools for working
with data so that they can get more done in less time, and with less pain. This workshop
teaches data management and analysis for genomics research including: 

- best practices for organization of bioinformatics projects and data, 
- use of command-line utilities, 
- use of command-line tools to analyze sequence quality and perform variant calling, 
- and connecting to and using cloud computing.  

This workshop is designed to be taught over two full days of work (excluding lectures).  
  
Interested in teaching these materials? We have an [onboarding video](https://www.youtube.com/watch?v=zgdutO5tejo) and accompanying [slides](https://docs.google.com/presentation/d/1fLlT2lPv32DqCFpRPPdHZBNHiQTpK79wd5Z3nsFwL3s/edit#slide=id.p) available to prepare Instructors to teach these lessons. After watching this video, please contact team@carpentries.org so that we can record your status as an onboarded Instructor. Instructors who have completed onboarding will be given priority status for teaching at centrally-organized Data Carpentry Genomics workshops.

## Getting Started

This lesson assumes that learners have no prior experience with the tools covered in the workshop.  
However, learners are expected to have some familiarity with biological concepts, including the concept of genomic variation within a population. Participants should bring their own laptops and plan to participate actively. 

## Data
 
This workshop uses data from a long term evolution experiment published in 2016: [Tempo and mode of genome evolution in a 50,000-generation experiment](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4988878/) by Tenaillon O, Barrick JE, Ribeck N, Deatherage DE, Blanchard JL, Dasgupta A, Wu GC, Wielgoss S, Cruveiller S, Médigue C, Schneider D, and Lenski RE. (doi: 10.1038/nature18959)  
  
All of the data used in this workshop can be [downloaded from Figshare](https://figshare.com/articles/Data_Carpentry_Genomics_beta_2_0/7726454). However to make things more convvenient and limit the time to download large files all data is provided locally in your cocalc home directory as well.  
More information about this data is available on the [Data page](https://aldertzomer.github.io/organization-genomics/data/).  

<br>

# Workshop Overview 

### Monday
Room BOL-2.068 & BBG-079
| **Time&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**| **Lesson** | **Overview** |
| :-- | :-- | :-- |
| Day 1 09:00-09:45 | Introduction to course | [**Michael**] |
| Day 1 10:00-10:30 | Introduction to day 1-3 | [**Alex** / Tim / Aldert] |
| Day 1 10:45-12:15 | [Project organization and management](https://aldertzomer.github.io/organization-genomics/) | Learn how to structure your metadata, organize and document your genomics data and bioinformatics workflow, and access data on the NCBI sequence read archive (SRA) database.|
| Day 1 12:15-13:00 | Break | Move to other building! |
| Day 1 13:15-14:00 | Introduction to LTEE | [**Tim**] |
| Day 1 14:15-16:00 | [Introduction command line (1-3)](https://aldertzomer.github.io/shell-genomics/)  +discussion |  Learn to navigate your file system, create, copy, move, and remove files and directories, and automate repetitive tasks using scripts and wildcards. |

  
### Tuesday
Room BOL-2.068
| **Time&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**| **Lesson** | **Overview** |
| :-- | :-- | :-- |
| Day 2 09:00-09:45 | Introduction research (NGS, quality, variant calling towards phylogenomics) | [Tim] |
| Day 2 10:00-12:15 | [Introduction command line (4-6)](https://aldertzomer.github.io/shell-genomics/) | Continue from Day 1 |
| Day 2 12:15-13:00 | Break |
| Day 2 13:15-16:00 | [Data wrangling and processing](https://aldertzomer.github.io/wrangling-genomics/) | Use command-line tools to perform quality control, align reads to a reference genome, and identify and visualize between-sample variation. |
| &nbsp;  &nbsp; | | |

  
### Wednesday
Room BOL-2.068 & BOL-1.055
| **Time&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**| **Lesson** | **Overview** |
| :-- | :-- | :-- |
| Day 3 09:00-09:45 | Introduction research (metagenomics and meta-barcoding) | [**Alex**] |
| Day 3 10:00-12:00 | [Data wrangling and processing](https://aldertzomer.github.io/wrangling-genomics/)  +discussion | Continue from Day 2 |
| Day 3 12:15-13:00 | Break |
| Day 3 13:15-16:00 |[Introduction to cloud computing for genomics](http://aldertzomer.github.io/cloud-genomics/) & self study | Learn how to work with Amazon AWS cloud computing and how to transfer data between your local computer and cloud resources - Only necessary when running this course on an AWS instance. 
  
<br>

# **Optional** Additional Lessons (Extra & Wednesday self-study)

| Lesson | Overview |
| :-- | :-- |
| [Bash scripting exercises: grep](https://ryanstutorials.net/linuxtutorial/grep.php) | Learn grep and **regular expressions** with examples 
| [Bash scripting exercises: sed](https://www.tutorialspoint.com/sed/) | sed tutorial for advanced learners
| [Bash scripting exercises: awk](https://www.tutorialspoint.com/sed/) | awk tutorial with many examples 
| [Putting your grep/sed/awk knowledge to the test](https://www.hackerrank.com/domains/shell?filters%5Bsubdomains%5D%5B%5D=grep-sed-awk) | Challenges for grep/sed/awk programmers. Requires a user account at [hackerrank](http://www.hackerrank.com)
| [Intro to R and RStudio for Genomics](https://datacarpentry.org/genomics-r-intro/) | Use R to analyze and visualize between-sample variation. Please note that workshop materials for working with Genomics data in R are in “alpha” development. In these lessons they instruct to do a local install or go to Amazon for Rstudio. Alternative you can use a FREE instance in the cloud at https://rstudio.cloud/ (preferred option) |
| [R for reproducible scientific analyses](https://swcarpentry.github.io/r-novice-gapminder/) | Fundamentals in R and tidyverse |

# Teaching Platform
This workshop is as much based on the original datacarpentries workshop however it was redesigned to be run on a [Cocalc instance (4)](https://cocalc4.science.uu.nl/) or [Cocalc instance (6)](https://cocalc6.science.uu.nl/) platform hosted at Utrecht University.
If you want to run your own instance of a similar server used for this workshop, follow the directions in the [Setup](setup.html) tab to generate an Amazon version (without the cocalc interface). 

