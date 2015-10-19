###Predicting Student Performance in edX using Browser Events
####By Joshua E. Jodesty

######This repository contains an IPython Notebook providing a walkthrough of my project, and a pdf presentation I delivered at Metis. The walkthrough and pdf provide actionable insights I've extracted from the student log dataset. NOTE: This pdf may contain descrepencies since this project is ongoing.

#####What I’ve done and why:
My Educational Data Mining research and unconventional education path ignited my passion for Data Science and the improvement of Education. For these reasons, I’ve decided to undertake a data science project that will enable educators to make more informed decisions towards improving student performance in e-learning environments. This project involves my analysis of anonymized student-level data from “massive open online courses,” otherwise known as MOOCs.

#####Data Scource & Overview: [dataverse.harvard.edu](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/26147) 
This dataset contains 129843 student logs from HarvardX and MITx MOOCs on edX. These logs mostly contain student behavior captured by browser events, measures derived from these events, anonymized student and course identifications, student demographics, and final grades.

#####Primary Objective:
The primary objective of my analysis is to deliver insights that will enable personalization of students' curriculum, instruction, and feedback suited to their study habits and demographic, and the opportunity to intervene when these habits and demographics are conducive to negative outcomes in MOOCs.

#####Secondary Objectives:
######A. Predict student outcomes in MOOCs offered by edX using varios classification techniques - Create, train, and test predictive models with student logs. These models will predict the outcomes of students performance in MOOCs. I define an outcome as whether a student recieves a certification, along with their grade range in the form of letter grades.

######B. Determine browser event phenomena that affects student outcomes, by determining significant features for model performance, and through exploratory data analysis.

#####Methodology Overview:
To accomplish this objective, I cleansed, transformed, explored, modeled, visualized, and interpreted student log data from HarvardX and MITx MOOCs on edX. I analyzed this data using Python, Pandas, NumPy, and SciKit-Learn in Jupyter’s IPython Notebook.

#####Solutions/Products:
#####1. Generated a predictive models that can efficiently predict student performance outcomes
#####2. Determined significant student behavior affecting their outcomes, as well as demographics correlated to it
#####3. Recorded unique characteristics of schools and courses hosted by edX.

#####Goal:
Enable educators to make more informed descision to improve student performance by providing actionable insights about student performance

#####Value of Analysis:
* Provide individualized feedback that will optimize their study habits.
* Customize students' e-learning experiences to suit their demographic.
* Intervene when students are exhibiting behavior and fit demographics conducive to negative outcomes in a MOOC

#####Challenges: 
* Determining student behavior that affects an individual student’s performance in a MOOC is partially a set of individualistic measurements of student access of a MOOCs “courseware,” and student evaluation methods employed for that MOOC.
  * Courseware is the curriculum content of a MOOC. The courseware of a MOOC implicitly indicates its curriculums delivery methods with content (resource, assignment, and assessment) types, counts, durations, and sizes.
  *	Student interactions with curriculum content in the courseware implicitly indicates their study habits.
*	These curriculum and study habit measures are exhibited by browser event logs of student interactions with the edX platform.
*	Student browser event trends, demographics, and outcome averages differ between MOOCs, schools, and MOOC platforms.
*	Since unique event trends of each MOOC determine overall student performance, demographics cannot be solely attributed to student performance. Therefore demographics must be considered in conjunction with attributes of specific MOOCs, offered by specific schools, and hosted on specific MOOC platforms. 

#####Methodology:
A. Explore, cleanse, & transform data

B. Discover trends

C. Create and evaluate multiple predictive models

D. Determine significant attributes for optimal model performance
