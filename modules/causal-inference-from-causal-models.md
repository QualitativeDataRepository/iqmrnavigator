---
layout: page
title: Causal Inference from Causal Models (Modules 18, 22, 26)
---

Monday, June 23; Tuesday, June 24; Wednesday, June 25
{: #module-date}

**Monday, June 23; Tuesday, June 24; Wednesday, June 25**

**Alan Jacobs (University of British Columbia)**

This module explores the use of causal models to design and implement qualitative and mixed-method empirical strategies of causal inference. A great deal of recent methodological progress in the social sciences has focused on how features of a research design – such as randomization by the researcher or by nature - can allow for causal identification with minimal assumptions. Yet, for many of the questions of greatest interest to social scientists and policymakers, randomization or its close equivalents are unavailable. We are, in short, often forced to rely on beliefs about how the world works - that is, on models. Based on the book *Integrated Inferences* by Macartan Humphreys and Alan Jacobs, this module examines how we can engage in systematic model-based causal inference. Specifically, we will explore how researchers can encode their prior knowledge in a causal model and learn about causation at the level of both individual cases and populations, using both qualitative and quantitative data. The advantages of this approach include making process tracing more analytically explicit and transparent, better connecting theory and data, and the integration of small-N and large-N methods in a manner that allows each approach to strengthen the other.  
  
For an overview of the book and this module, students can watch this short introductory video: [https://youtu.be/mRAkP7ZC9G4?si=DP-UFBY3E5iKqOCs](https://youtu.be/mRAkP7ZC9G4?si=DP-UFBY3E5iKqOCs)

The focus of this module will be on a theoretical, conceptual, and intuitive understanding of how causal inference from causal models works, though the material is somewhat technical in nature. Later in the summer, students will also have the opportunity to take a free, online module that will teach how to implement the method using the [CausalQueries](https://cran.r-project.org/web/packages/CausalQueries/index.html) R package that accompanies the book. Further details about the online workshop will be shared separately.

For those who do not wish to purchase Humhpreys and Jacobs’ *Integrated Inferences* (H&J below)*,* from which the required readings come, a free, full-text version of the book can be found on the book’s website, here:

[https://integrated-inferences.github.io/book/](https://integrated-inferences.github.io/book/)

All assigned videos can be found here: [https://www.youtube.com/@IntegratedInferences](https://www.youtube.com/@IntegratedInferences)

***Participants who did not attend the module sequence from the beginning may not join later in the sequence.***

## What Is a Causal Model? (M18, June 23)
{: .module-sub }

### 8:45am - 10:15am – Causal Model Basics


In this session, we will learn the “nuts and bolts” of causal models and their graphical counterparts, directed acyclic graphs (DAGs). How can we formalize our beliefs about relationships in a given domain in the form of a causal model? What does and does not need to be specified when writing down a causal model? What are the rules for visually representing causal dependencies in a DAG? How can a more detailed causal model underwrite, or imply, a less-detailed one? And how can we represent causal estimands of interest – such as a case-level causal effect, a causal pathway, or an average causal effect – within a causal model?

**Required readings:**

  - Watch videos 1 and 2

  - H&J, Chapters 1 and 2

### 1:30pm - 3:00pm – Make Your Own Model


In this session, students will have a chance to write down their own causal models and draw the associated DAGs, formally encoding their own beliefs about causal relationships in a domain of interest to them. This will be an opportunity to work through some of the choices that researchers confront when constructing causal models.

**Required readings:**

  - H&J, Chapter 3

### 3:30pm - 5:00pm – What Can a Causal Graph Tell Us?


In this session, we will examine what we can learn about research design from a graphical representation of a causal model. In particular, we will explore the property of “d-separation,” which allows one to read relations of conditional independence off of the structure of a properly constructed DAG. We will then assess how understanding relations of conditional independence can help us identify potentially informative pieces of data for a given causal estimand – that is, how causal models can help us figure out what it is we want to observe. We will practice reading a causal graph with group exercises.

## Causal Models for Case-Level Inquiry (Process Tracing) (M22, June 24) 
{: .module-sub }

### 8:45am - 10:15am – Building in the Potential Outcomes Framework


This session will introduce the theory of causation that we will be using in the causal-models setting: the potential outcomes framework. We will then show how we can embed causal relationships, as potential outcomes, into a DAG by allowing for the operation of a set of “nodal types” at each node in the graph. Group exercises will reinforce the core ideas.

### 1:30pm - 3:00pm – Causal Questions about Cases


In this session, we start to explore how we can undertake case-study research – and, specifically, use the tool of process-tracing – using causal models. We begin by unpacking the different kinds of causal questions that we can ask about individual cases. These include questions about causal effects, causal explanation, and causal pathways or mechanisms. How do we define case-level causal questions in the context of a causal model? We will practice defining questions together with worked examples.

**Required readings:**

  - Video 3

  - H&J, Chapter 4

### 3:30pm - 5:00pm – Process-tracing with a causal model


*We then turn to a step-by-step introduction to how we can use causal models to conduct systematic, analytically explicit process tracing to answer the case-level causal questions that we have. We will discuss how to formally embed prior theoretical beliefs into our causal models and how we then draw inferences about the questions of interest once we make observations of the case we are studying.*

**Required readings:**

  - Video 4

  - H&J, Chapters 7 and 8

## Mixing Methods with Causal Models (M26, June 25) 
{: .module-sub }

### 8:45am - 10:15am – Updating Our Models with Data from Many Cases


When we conduct process tracing, we take the model as given and apply it to the case at hand. We do not learn about the model itself. However, when we are studying many cases, we can use data from those cases to update the model – that is, to learn about the model from the cases. This allows us to draw population-level inferences and to integrate findings across methods. In this sessions, we will provide key intuitions for how we learn about our model from data. How do data allow us to adjust our beliefs about causal effects operating within our model? For instance, how does learning about a mediator variable in a causal model (say, between X and Y) provide leverage on X’s effect on Y? And, comparing single-case to multi-case inference, how exactly does process tracing differ from larger-N inference in the causal models approach?

### 1:30pm - 3:00pm – Answering Population-level Questions 


Building on the morning session, we now ask how we can both ask and answer population-level questions using causal models. These include questions about average causal effects, about the proportion of effects that are of different kinds (e.g., in what proportion of cases are there positive effects as compared to no effect), and questions about the pathways or mechanisms through which effects unfold. How are such questions defined? What form do the answers take? And how do we interpret the results we get?

**Required readings:**

  - H&J, chapters 9 and 10

### 3:30pm - 5:00pm – Mixing Methods with Causal Models


A common form of mixing methods involves combining two different data strategies: bringing together intensive investigation of a small number of cases (small-N process tracing) with thinner data across a large set of cases (large-N analysis). In this session, we show how the causal-models approach provides a systematic, analytically transparent way of combining the information from intensive and extensive approaches. We also show how integrating inferences in this way allows each method to strengthen the other: intensive case analyses allow us to improve causal inferences across a large sample, while learning about the model from a large set of cases allows us to ground process tracing in evidence.