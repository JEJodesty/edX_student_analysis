###Predicting Student Performance in edX using Browser Events
####By Joshua E. Jodesty

######Data Scource:
[dataverse.harvard.edu](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/26147) - 129843 Student logs from HarvardX and MITx MOOCs on edX containing student behavior captured by browser events, student demographics, and final grades.

#####Objectives:
######A. Predict student outcomes in MOOCs offered by edX by performing classification techniques on student behavior captured by browser events, student demographics, and final grades - Create, train, and test predictive models with student logs.
* Outcomes: Certifications & Grade Range

######B. Determine browser event phenomena that affects student outcomes, by determining significant features for model performance, and through exploratory data analysis.

#######Goal:
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

#####This repository contains an IPython Notebook providing a walkthrough of my project, and a pdf presentation I delivered at Metis. The walkthrough and pdf provide actionable insights I've extracted from the student log dataset.
