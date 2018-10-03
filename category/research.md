---
layout: category
title: Research
---

### Grade Prediction
The Grade Prediction Project (GPP) was developed as a way of using machine learning to provide
an early warning system to introductory physics courses. Using registrar data and in course variables
we built series of models based on what is known in weeks 1-5 of the introductory physics series.
These models can, with reasonably high accuracy (70%-80% in physics 1, 80%-90% in Physics 2), predict if a student will get less than a B in the course. As most instructors often have to wait for the midterms to have a good idea of which students need help, it
is our belief that with these models interventions can be targeted much earlier and in-danger students 
can get the help they need before it is too late to change their course trajectory.

See the [code](https://github.com/cabotzabriskie/Grade-Prediction-Project)

### Multi-Dimensional Item Response Theory

The Multi-Dimensional Item Response Theory (MIRT) projects were developed to uncover the factor structure of the most commonly used conceptual inventories in physics education: the Force Concept Inventory (FCI) and the Conceptual Survey of Electricity and Magnetism (CSEM). MIRT, which fits individual logistic models to each question (or item) represents a novel approach to factor analysis and is especially well suited for instruments not designed with a factor structure in mind. Using MIRT we were able to build highly statistically significant confirmatory models of both the FCI and the CSEM.

You can read the MIRT FCI paper [here](https://journals.aps.org/prper/abstract/10.1103/PhysRevPhysEducRes.14.010137)

The MIRT CSEM paper is currently under review.

### Predicting Graduation Success

The goal of this project is to build a robust statistical model of STEM student graduation which will allow us to identify variables related to students successfully completeing STEM degrees as well as find points in the college experience of STEM students where attrition is the greatest. This represents the largest of the projects in our research group and only a part of the analysis has been completed to date. Because of the complexity of the data, standard statistical techniques such as linear regression were deeming insufficient to extract useful conclusions from the data.

One piece of this project involves developing machine learning models that predict both graduation with STEM degrees and graduation with only Engineering degrees in two separate ways, first an overall picture ignoring the effect of time and second, at three points in a student's academic career: at entry to the university, after the first semester of study, and after the second semester of study.The time independent models performed very well with accuracies of 89% when using all variables at our disposal. The "windowed" models also performed well with between 70%-80% accuracy. Both of these models provide insight into the degree to which registrar level variables held by universities can be used to understand retention. As our database of survey data grows, we intend to combine both datasets to develop a more complete picture.


