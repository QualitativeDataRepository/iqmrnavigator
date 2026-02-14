---
layout: page
title: Module Prerequisites
---


Some of IQMR’s module sequences have prerequisites that need to be completed in advance of the Institute beginning. 
O
Participants who plan to take modules with prerequisites **are required** to either take a short (asynchronous) online workshop providing basic familiarity, or demonstrate their pre-existing knowledge of the software, by **June 8, 2026**.

IQMR will also offer participants the opportunity to attend drop-in office hours for additional help with some of these software packages. Details on those office hours will be provided here in the coming months.

These are the relevant module sequences, tools, prerequisites, and ways to demonstrate that you have completed the prerequisite:

## M4, M8 Ethnography 

### Prerequisite 
Before coming to IQMR, spend at least four hours intentionally observing and/or participating in, and then reflecting on a community, group, space, place, behavior, or cultural practice. Take detailed notes on what you observe and what you experience. Feel free to explore any overarching patterns, themes, hypotheses, or understandings that emerge over the course of your notes.

  - There must be **no reasonable expectation of privacy at your site**, or among the individuals who you may observe. One way to ensure this is to choose to conduct your observations in a public space, meaning that there are no formal, institutional, or legal barriers to access (e.g., no permission, application, ID required, or sign-up/sign-in required).

  - The site that you choose to observe must be **low-risk for you and for participants**. Remember, ethnography embraces the presence of politics in the everyday and the banal.

  - **You must engage only in observation or public participation.** This exercise asks you to practice observation. Your goal is to work on **noticing** aspects of the everyday through the eyes of a social scientist. **Absolutely no interviews or focus groups may be conducted for this exercise.**

  - **Before beginning observation**, please write the following document and send it to the instructors for sign off ([sparkinson@jhu.edu](mailto:sparkinson@jhu.edu) and [kbond@binghamton.edu](mailto:kbond@binghamton.edu)). You should not begin the observation portion of the exercise without sign off. Please then bring this document and your notes with you to the module meetings:
    
      - An approximately half-page document detailing the logic of your siting, the behaviors/processes you intend to observe, and the populations you expect to be present, and any advance expectations or assumptions you have regarding what you will observe.
    
      - An approximately half-page document detailing your understanding of the risks, costs, and potential safety and security complications associated with your choice of a site and topical focus.

  - Previous, group versions of this exercise have resulted in students being approached, detained, or otherwise surveilled by public law enforcement or private security agents for the appearance of note taking or otherwise “suspicious-looking” behaviors. These incidents occurred at shopping malls. However, they could take place in any number of locations and could involve actors other than law enforcement. This is one reality of observational/immersive research that we will discuss further in class. Keep this reality in mind as you plan your work.

  - Understand that any notes you take do not qualify as human subjects research, do not have IRB approval, are not legally protected from subpoena, and could be used as evidence against you or those you observe by authorities. Please use this knowledge to inform your choice of observation site.


## M17 / M21 / M25 -- Integrating Qualitative and Experimental Methods (Carter and Tunon)

### Prerequisite 
The module sequence will assume a basic understanding of the potential outcome framework of causation. The instructors have <a href="https://www.dropbox.com/scl/fi/5h1rk32m304n1d2g2o0vz/potential_outcomes.mp4?rlkey=m4n1nwpwgc6kjw10adx4fhcpc&st=k2l7kl1v&dl=0" target="_blank">created a videos</a> introducing these concepts.

### Demonstration of completion of prerequisite: 
Complete [this short problem set](/assets/documents/potential_outcomes_pset.pdf){: target="_blank"} on the potential outcomes and upload your solution (as a Word or PDF file or a picture of your handwritten solution) to [the module prequisites form](https://syracuseuniversity.qualtrics.com/jfe/form/SV_0MJlWiOmAowyjpY){: target="_blank"}.

---- 

## M2 / M6 -- Introduction to Text as Data (Shen-Bayh)

### Prerequisite 
    
The “Text as Data” module sequence assumes basic familiarity with python, in particular
1.	Python basics, including how to do a basic `for` loop, function writing, loading data.
2.	Pythonic data structures, including lists, tuples, dictionaries, and dataframes.
3.	How to manipulate string objects in Python.

If you’ve done any programming in python in the past, you will be fine. Otherwise, we recommend working through the free, interactive lesson  “Learn String Manipulation by Building a Cipher” on Free Code Camp. For the course, you will work in a Jupyter Notebook on Google Collab. 

*This is an introductory course and the prerequisite is intended as a low hurdle for participation. Please don't let it dissuade you from taking the course*


### Demonstration of completion of prerequisite
To demonstrate basic proficiency, please upload a screenshot of your solution to the following task running in Google Collab to [the module prequisites form](https://syracuseuniversity.qualtrics.com/jfe/form/SV_0MJlWiOmAowyjpY){: target="_blank"}. Please don’t just use an LLM to write your answer: you’re not doing yourself a favor. We will have office hours in the 2 weeks prior to IQMR to help you if you’re struggling.


Write a function called analyze_grades that:
1. Takes a list of student grade records (list of dictionaries)
2. Cleans and processes the data
3. Returns summary statistics
    
**Sample data:**

    students = [
        {"name": "JANE SMITH", "grade": 85, "major": " sociology "},
        {"name": "JOHN DOE", "grade": 92, "major": "political science"},
        {"name": "MARY JOHNSON", "grade": 78, "major": " Economics "},
        {"name": "BOB WILSON", "grade": 88, "major": "sociology"}
    ]
    

**Expected output:**
    
    {
         'total_students': 4,
         'average_grade': 85.75,
         'student_names': ['jane smith', 'john doe', 'mary johnson', 'bob wilson'],
         'majors': ['economics', 'political science', 'sociology']
     }
    

----


