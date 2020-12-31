# Project SE4ML4EDU

## Introduction

Over the last decade, machine learning and data science (ML for short) have become an integral part of software engineering and computer science curricula, among others [1][2][3]. As a result, teachers and researchers put a lot of time and effort into creating ML-educational materials, thereby employing different kinds of tools and techniques – most notably Jupyter Notebook, TensorFlow and Keras. Apart from the mathematical foundations of ML, subject of these materials typically seem to include data mining and sanitation, regression and classification analysis, deep learning and neural nets, and hyperparameter tuning.

It is our intuition, however, that in this educational setting, little or no attention is given to the operational aspects of ML-related projects. Jupyter Notebooks, for example, is a perfect tool for experimenting and testing, but fails to deliver as a production platform. Consequently, students and teachers alike typically transform their Notebooks to plain (Python)-scripts to be run directly from the command line. A procedure that works fine for relatively simple or standard projects, but which does not take into account a variety of questions that emerge once one want to deploy the code to production. Question such as

- how do you maintain and version the data that the code is trained on?
- how do you maintain and version the code itself?
- how to retain and save a trained model?
- how to put a trained model into production?
- how does the model performs with a lot of concurrent users?

These kind of questions typically find an answer in the field of DevOps and software engineering. Thus, in the industry we can witness several attempts to bring these fields together [4][5][6]. However, academia seems to be lagging behind in this respect.

It is the goal of the project under consideration to remedy this situation.


## The project: SE4ML4EDU

The project SE4ML4EDU consists of three parts: a *descriptive*, a *prescriptive*, and a *curative* part. The results of all these sub-projects will be shared via the known channels, using a creative commons license. 

### Part 1: inventory of the current state of affairs of ML education in The Netherlands

In the first sub-project, as much information as possible about ML education in The Netherlands is obtained. In order to do this, a questionnaire will be developed and send to Software Engineering and Computer Science departments of universities and other higher educational institutions. This questionnaire will not only focus on the tools and techniques that are employed; it will also ask about the degree to which SE-principles are incorporated in the ML curricula.

As part of the questionnaire, respondents will be asked whether they are willing to participate in a further personal interview. On basis of this, interviews with specific teachers and researchers will be conducted in order to obtain more in-depth information about the diverse opinions and considerations that have led to the organization of the curricula. 

This sub-project will eventually lead to a little article on and a presentation of the current state of ML education in The Netherlands.


### Part 2: creation of a syllabus

The information gathered in the first sub-project will be further analyzed with regards to software engineering practices for ML [7], in order to get a clear view of the amount to which these principles are part of the current ML curricula. This analysis will result in an overview of SE-aspects that are already part of the curricula, and parts that are missing.

On basis of this overview, we will write a syllabus that will help teachers and researchers to enhance their ML-materials with SE practices. In this syllabus, we will use the IEEE SWEBOK [8] to come up with learning outcomes that are specifically targeted at the current state of ML-education in The Netherlands.


### Part 3: creation of a slide-deck

The syllabus that is the result of the second sub-project will be used to create a set of presentations (a *slide deck*) that teachers and researchers can use to further their ML education with SE4ML tools and techniques. Using the information gathered in both sub-projects, this slide deck aims at a practically seamless integration in standing educational practices.



## Planning

In broad terms, the general planning of the project is as follows:

Start project: Februari 2021
End sub-project 1: June 2021
End sub-project 2: October 2021
End sub-project 3: January 2022

## References

[1] https://www.hbo-kennisbank.nl/searchresult?q=machine+learning

[2] https://www.eur.nl/erasmusacademie/cursus/opleiding-data-science-predictive-machine-learning

[3] https://www.rug.nl/bachelors/artificial-intelligence/?lang=en

[4] https://se4ml.org/

[5] https://se-ml.github.io/

[6] https://www.forbes.com/sites/forbestechcouncil/2020/12/23/what-leaders-need-to-know-about-mlops/

[7] https://se-ml.github.io/report2020

[8] https://www.computer.org/education/bodies-of-knowledge/software-engineering/v3

s

