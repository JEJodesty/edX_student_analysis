### Predicting Student Performance in edX using Browser Events
#### By Joshua E. Jodesty

###### This repository contains an [IPython Notebook](https://github.com/JEJodesty/edX_student_analysis/blob/master/edX_Student_Analysis.ipynb) walkthrough of my project, and a pdf presentation I delivered at Metis. The walkthrough and pdf provide actionable insights I've extracted from a student log dataset. NOTE: The notebook and pdf may contain descrepencies since this project is ongoing.

##### What, Why, & How:
My Educational Data Mining research and an unconventional education path ignited my passion for Machine Learning and the improvement of Education. For these reasons, I’ve decided to undertake a data science project that will enable educators to make more informed decisions towards improving student performance in e-learning environments. This project involves my analysis of anonymized student-level data from “massive open online courses,” otherwise known as MOOCs. I've cleansed, transformed, explored, modeled, visualized, and interpreted student log data from HarvardX and MITx MOOCs on edX, using Python, Pandas, NumPy, and SciKit-Learn in Jupyter’s IPython Notebook.

##### Data Scource & Overview:  
The [dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/26147) contains 129843 student logs from HarvardX and MITx MOOCs on edX. These logs mostly contain student behavior captured by browser events, measures derived from these events, anonymized student and course identifications, student demographics, and final grades.

##### Primary Objectives of my analysis:
###### 1. To deliver insights that will enable the personalization of students' curriculum, instruction, and feedback. These personalized learning experiences are to be suited to their study habits and demographics, which I analyze in this project.
###### 2. To deliver insights that will enable educators to intervene when students' study habits and demographics are conducive to negative outcomes in MOOCs.

##### Secondary Objectives of my analysis:
###### 1. Predict student performance outcomes in MOOCs offered by edX
I define an outcome as whether a student recieves a certification, along with their grade range.
###### 2. Determine student behavior, curriculum delivery methods, and demographics conducive to positive and negative performance outcomes in MOOCs. 
Student behavior is captured by their browser events. In this case, browser events reffer to students’ interactions with the edX platform in their web browser. These are primarly interactions with curriculum content in the “Courseware” tab. These interactions implicitly measure their study habits and curriculum delivery methods

##### Current Solutions/Products:
###### 1. Trained, tested, and evaluated predictive models that can efficiently predict student performance outcomes in MOOCs offered by edX.
* **Created models using Random Forest Classifier that correctly classifies the outcomes of 95.55% of students in a course and 92.86% of students in a school.**

###### 2. Determined significant browser event phenomena and curiculum delivery methods affecting their outcomes, as well as demographics correlated to it. 

###### 3. Recorded unique characteristics of schools and courses hosted by edX.

##### Considerations: 
*	Curiculum delivery methods differ between MOOCs, schools, and MOOC platforms. This in-turn affets student peroformance and browser event trends.
*	Since unique event trends of each MOOC determine overall student performance, demographics cannot be solely attributed to student performance. Therefore demographics must be considered in conjunction with attributes of specific MOOCs, offered by specific schools, and hosted on specific MOOC platforms. 

##### Appendix:
**Browser Events** - In this case, browser events reffer to students’ interactions with the edX platform in their web browser, which include interactions with curriculum content in the “Courseware” tab. Browser events can be mouse clicks and hovers, button presses, etc. In this case, browser events represent students’ interactions with the edX platform in their web browser. Browser events can be mouse clicks and hovers, button presses, etc. Also in this case, browser events are subjected to interactions with specific content in the “courseware”. Types of browser events include the numbers of videos played, posts in the course forum, and overall interactions. The student account measurements are aggregated from browser events. These measures include the numbers of days students interact with the courseware in a single course, and whether they accessed more than half of the chapters.

**Generated Features** - grade ranges in the form of letter grades; whether a student received a certification along with their letter grade (“outcome”); age ranges; percentages of chapters viewed; proportions of events that were video plays, and forum posts; overall events, video plays, and forum posts per day; the number of days videos where played, and content was posted in the forum; etc.
