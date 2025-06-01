---
layout: page
title: Module Prerequisites
---


Some of IQMR’s module sequences have prerequisites that need to be completed in advance of the Institute beginning. For the pre-Institute assignment required for the Ethnographic Methods module sequence, please see [the module sequence description](/modules/ethnography#preparation-required) for details and deadlines.

Other module sequences, listed below, require participants to have basic familiarity with some content, such as a programming language or basic statistical concepts. This requirement helps to ensure that the modules are maximally useful for everyone, focusing on methods and techniques, and not basic instruction in how to use the software.

Participants who plan to take modules with prerequisites **are required** to either take a short (asynchronous) online workshop providing basic familiarity, or demonstrate their pre-existing knowledge of the software, by **June 8, 2025**.

IQMR will also offer participants the opportunity to attend drop-in office hours for additional help with some of these software packages. Details on those office hours will be provided here in the coming months.

These are the relevant module sequences, tools, prerequisites, and ways to demonstrate that you have completed the prerequisite:

## M17 / M21 / M25 -- Integrating Qualitative and Experimental Methods (Carter, Crabtree, Rizzo, Tunon)

### Prerequisite 
The module sequence will assume a basic understanding of the potential outcome framework of causation. The instructors have <a href="https://www.dropbox.com/scl/fi/tpjar9wmndvasxynrttkc/potential_outcomes.mp4?rlkey=lzbfjcborlvb4b0bjnaa4ol2m&dl=0" target="_blank">created a videos</a> introducing these concepts.

### Demonstration of completion of prerequisite: 
Complete [this short problem set](/assets/documents/potential_outcomes_pset.pdf){: target="_blank"} on the potential outcomes and upload your solution (as a Word or PDF file or a picture of your handwritten solution) to [the module prequisites form](https://syracuseuniversity.qualtrics.com/jfe/form/SV_0MJlWiOmAowyjpY){: target="_blank"}.

---- 

## M2 / M6 -- Text as Data (Shen-Bayh)

### Prerequisite 
    
The “Text as Data” module sequence assumes basic familiarity with python, in particular
1.	Python basics, including how to do a basic for loop, function writing, loading data.
2.	Pythonic data structures, including lists, tuples, dictionaries, and dataframes.
3.	How to manipulate string objects in Python.

If you’ve done any programming in python in the past, you will be fine. Otherwise, we recommend working through the free, interactive lesson  “Learn String Manipulation by Building a Cipher” on Free Code Camp. For the course, you will work in a Jupyter Notebook on Google Collab. 


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


