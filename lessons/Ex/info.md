# Experiment Design and Recommendation Engine
## I. Concepts of Experiment Design
Here you will learn about what it means to run an experiment, and how this differs from observational studies. Topics include not only what to include in an experimental design, but also what to watch out for when designing an experiment. 

Type of Study

While a quasi-experiment may not have the same strength of causality inference as a true experiment, the results can still provide a strong amount of evidence for the relationship being investigated. This is especially true if some kind of matching is performed to identify similar units or groups. Another benefit of quasi-experimental designs is that the relaxation of requirements makes the quasi-experiment more flexible and easier to set up.

Additional Reading 
This fascinating New York Times article details different ways of investigating the claim that Nike's Vaporfly running shoes provide a significant advantage in running speed, despite not being able to run a true, randomized experiment. 
Nike Says Its $250 Running Shoes Will Make You Run Much Faster. What if That’s Actually True? (Published 2018)
Types of Experiment
 Between-subjects experiment （A/B test）：each unit only participates in, or sees, one of the conditions being used in the experiment
 within-subjects design (repeated measures design)
Side Note: Factorial Designs manipulate the value of multiple features of interest
Types of Sampling

Side Note: Non-Probabilistic Sampling ( convenience sample)
Measuring Outcomes
Evaluation metric


Side Note: Alternate Terminology 
You might hear other terminology for goals and evaluation metrics than those used in this course. In the social sciences, it's common to hear a "construct" as analogous to the goal or objective under investigation, and the "operational definition" as the way outcomes are measured. For example, the construct of "reaction time" could be operationally defined as "time in milliseconds to click on the correctly indicated button." 

In general company operations, you might encounter the terms "key results" (KRs) or "key performance indicators" (KPIs) as ways of measuring progress against quarterly or annual "objectives." These objectives and KRs / KPIs serve a similar purpose as study goals and evaluation metrics, and might even be driving factors in the creation of an experiment. 
Creating Metrics

Funnels
Unit of Diversion
 Event-bases diversion
Cookie-based diversion
Account-based diversion
Invariant and Evaluation Metrics
Controlling Variables

If we aren't able to control all features or there is a lack of equivalence between groups, then we may be susceptible to confounding variables
Reference: 
Correlation does not imply causation  - Reference page with examples of how an observed correlation between two features might come about.
Checking Validity



Checking Bias


A novelty effect is one that causes observers to change their behavior simply because they're seeing something new. 

Ethics in Experimentations
Minimize participant risk
Have clear benefits for risks taken
Provide informed consent
Handle sensitive data appropriately

SMART Mnemonic for Experiment Design 
There's a mnemonic called SMART for teams to plan out projects that also happens to apply pretty well for creating experiments. The letters of SMART stand for: 
Specific: Make sure the goals of your experiment are specific.
Measurable: Outcomes must be measurable using objective metrics
Achievable: The steps taken for the experiment and the goals must be realistic.
Relevant: The experiment needs to have purpose behind it.
Timely: Results must be obtainable in a reasonable time frame.

## II. Statistical Considerations 
in TestingIn this lesson, you will learn about statistical techniques and considerations used when evaluating the data collected during an experiment. It is expected that you come into the course with knowledge about inferential statistics; the content here will see you applying that knowledge in different ways. 

Practical significance
Practical significance  refers to the level of effect that you need to observe in order for the experiment to be called a true success and implemented in truth. Not all experiments imply a practical significance boundary, but it's an important factor in the interpretation of outcomes where it is relevant.

Confidence interval is fully in practical significance region 
(Below, m_0m0 indicates the null statistic value, d_{min}dmin the practical significance bound, and the blue line the confidence interval for the observed statistic. We assume that we're looking for a positive change, ignoring the negative equivalent for d_{min}dmin.) 

If the confidence interval for the statistic does not include the null or the practical significance level, then the experimental manipulation can be concluded to have a statistically and practically significant effect. It is clearest in this case that the manipulation should be implemented as a success. 
Confidence interval completely excludes any part of practical significance region 

If the confidence interval does not include any values that would be considered practically significant, this is a clear case for us to not implement the experimental change. This includes the case where the metric is statistically significant, but whose interval does not extend past the practical significance bounds. With such a low chance of practical significance being achieved on the metric, we should be wary of implementing the change. 
Confidence interval includes points both inside and outside practical significance bounds 

This leaves the trickiest cases to consider, where the confidence interval straddles the practical significance bound. In each of these cases, there is an uncertain possibility of practical significance being achieved. In an ideal world, you would be able to collect more data to reduce our uncertainty, reducing the scenario to one of the previous cases. Outside of this, you'll need to consider the risks carefully in order to make a recommendation on whether or not to follow through with a tested change. Your analysis might also reveal subsets of the population or aspects of the manipulation that 
do  work, in order to refine further studies or experiments.

## III. A/B Testing Case Study
Here, you will put your skills to work to analyze data related to a change on a web page designed to increase purchasers of software. 
At the end of these lessons, you can complete an optional Portfolio Exercise in coordination with our industry partner Starbucks. In the project, you will learn more about how Starbucks conducts experiments. You will also get access to data related to a hiring screen that was once conducted by Starbucks to test ideas related to experimental design and statistical metrics. 

# Recommendation Engines 
I. Introduction to Recommendation Engines
In this lesson, you will learn about the main ideas associated with recommendation engines. This includes techniques and measures of effectiveness. 
II. Matrix Factorization for Recommendations
Extending on the previous lesson, you will learn about one of the most popular techniques for recommendation engines known as FunkSVD. You will also complete a class that brings together a number of techniques to make recommendations for a number of different scenarios. 

