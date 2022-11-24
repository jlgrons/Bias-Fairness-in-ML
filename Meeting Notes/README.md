# Meeting Notes

## 08/16/22

* Papers to review:
  * start with the [calibration overview](https://academic.oup.com/jamia/article/27/4/621/5762806) from last time; this is the style of paper we are going for
  * search JAMIA website to see what exists there on fairness
  * [bias in real life](https://www.science.org/doi/abs/10.1126/science.aax2342)
  * [early fairness paper](https://arxiv.org/pdf/1805.12002.pdf)
  * [overview paper](https://www.annualreviews.org/doi/pdf/10.1146/annurev-statistics-042720-125902)
  * [overview paper](https://fairware.cs.umass.edu/papers/Verma.pdf)
  * [overview paper](https://www.nature.com/articles/s41598-022-07939-1) - See references therein
* A comparative analysis of the various metrics can be found in this [paper](https://arxiv.org/pdf/2001.07864.pdf)


## 09/15/22
* Papers read: Calibration tutorial paper and "Dissecting racial bias in an algorithm used to manage the health of populations", in the process of reading "Why Is My Classifier Discriminatory?"
* For next week: "Why Is My Classifier Discriminatory?" and "Algorithmic Fairness: Choices, Assumptions, and Definitions"

## 09/28/22
* Updates: Created overleaf document to store notes for literature review. 
* Papers read: "Why Is My Classifier Discriminatory", "Algorithmic Fairness: Choices, Assumptions and Definitions", "Fairness Definitions Explained", in the process of reading "A Clarification of the Nuances in the Fairness Metrics Landscape"
* Next week: Finishing up "A Clarification of the Nuances in the Fairness Metrics Landscape", "Fairness Metrics: A Comparative Analysis" and looking into their references/searching what else is on JAMIA. 
* Questions:
    * What application will we be using for the tutorial paper? How do we select which metrics of bias and fairness we want to discuss in the paper? 

## 10/06/22
?

## 10/13/22
* Discuss [presentation](https://github.com/jlgrons/Healthcare-DataScience-Reading-Group/tree/main/Fall%202022%20Slides)

## 10/27/22
* Research project course is the same form as the reading group, they didn't ask for anything else so I can forward you the email and we can submit that as a course so I can continue in the Winter
* For the statistical metrics section, do we want definitions described in words or just formulas? Are we using phenotyping as the main example because I can add in a sentence on how to interpret each metric with regards to the example?
* Should I change the example in the metric definitions to be the phenotyping example?
* I restructured a bit, I added a Background section with subsections for our simulated data, notation, the metrics and then we can go into the three metrics we consider
* Next Steps:
    * Write calibration section
    * When should we start working on the simulated study? 
    
 ## 11/03/22
* Should we keep the title as predictive parity if I am adding all of these other metrics to it? Should our sections be similar to the fairness paper? What is the difference to the fairness paper besides the example? 
* Next Steps:
    * Finishing completing the table
    * Updating example with phenotyping 
    * Calibration section
* Jesse: paper to read for [context](https://www.sciencedirect.com/science/article/pii/S1532046420302495)

## 11/17/22
* Paper updates:
    * Finished the table - not sure if the indicator functions are the best way to define the empirical estimates
    * Updated the metrics section to include definition, intuition and example 
    * Started working on the incompatibility of metrics section
* Questions about incompatibility of metrics section:
    * In _A clarification of the nuances in the fairness metrics landscape_, they discuss that separation and suffiency are incompatible if the distribution of (A, S, Y) is strictly positive - what does that mean? 
    * How should we format this section? Should I begin with the COMPAS example since that originates this discussion? Should I list conditions under which certain metrics are incompatible? Should we show any mathematics for this? 
    * I figured we would show how some definitions don't hold simultaneously using the simulation but should we show other examples? 
* Interested in helping with other projects to try and figure out what type of research I'd like to pursue for a PhD 
* Simulation Study: Reviewed the calibration tutorial and how they created their simulation study as a starting point to discuss further during meeting

## 11/24/22
* Updates: 
    * Written an outline for introduction
    * Created the fairness metrics R file (HelperFunctions)
    * Started to work on DataGeneration → in the R code in the repo, it uses logit and the gumbel → wanted to know the logic behind that and if we follow similar logic for our model?
    * Created a run_simulation R file and Rmd file
    * What model are we going to use for prediction? 
