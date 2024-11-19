# Matching Job Descriptions to CVs

**Project Description**  
This project is set in a context where we have many resume pdf's and their corresponding json transcriptions which we have to match to the department the potential employee would best fit. Using the appropiate natural language processing (NLP) techniques I was able to relate each CV to one of 24 categories using with a high degree of accuracy. I include the data and notebook I developed, with the EDA and justifications along the way.

## Table of Contents
- [Installation](#installation)
- [Results](#results)

## Installation

Ssteps to install and run the project locally. List dependencies and steps.

```bash
git clone https://github.com/edu-r0driguez/MatchCV2Department.git
cd MatchCV2Department
-- create a virtual environment to include all the necessary dependencies 
pip install -r requirements.txt
```
You need a Python version of 

## Results

By encoding each of the categories within the CV separately, the model was able to contextualize words and therefore gain a deeper understanding of their relevance to one category or the other. The obtained accuracy is of 83.9% with a top3 of 93.76%. This model could be part of a larger pipeline of a multimodal automatic resume processing software. 


