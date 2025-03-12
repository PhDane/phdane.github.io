---
layout: post
title: Azjen 1991 - The Theory of Planned Behavior
date: 2022-06-16 12:00:00 -0600
categories: [Comps]
tags: [comps, jdm, quantitative model, norms, attitudes, control, great paper]
math: true
---
[Google Scholar Link](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=the+theory+of+planned+behavior&btnG=)

Ajzen, I. (1991). The theory of planned behavior. Organizational Behavior and Human Decision Processes, 50(2), 179–211.

![The Theory of Planned Behavior](/images/TheoryOfPlannedBehavior.png){: style="max-width: 80%"}

## Summary
In terms of predicting action in specific situations, both disposition and personality traits have low accuracy, though their influence can be seen by observing behavior over a longer period of time.  According to the **theory of planned behavior**, _intention_ is central to the process of conscious thought translating into behavior.  Stronger intention increases the probability of the behavior being completed.  Intention takes into account a number of factors which either strengthen or weaken it.

The theory of planned behavior specifies three specific factors that influence intention - perceived behavioral control, subjective norms, and attitudes towards the behavior.  **Perceived behavioral control** refers to an individual’s belief concerning “the ease or difficulty of performing the behavior of interest” and the individual’s action-specific success expectancy.  It differs from the concept of _locus of control_ in that locus of control is generally longitudinally stable, while perceived behavioral control is specific to both situation and action.  Perceived behavioral control shares common ground with both todo: link Bandura’s theory of self-efficacy (which is cited) and todo:link Seligman’s concept of learned helplessness (which is not).  With intention being constant, increased perceived behavioral control will result in increased effort.  In terms of empirical measurement and prediction, “perceived behavioral control can often be used as a substitute for a measure of actual control.”

**Subjective norms** differ from social norms in that they deal specifically with the individual-level perceptions, rather than group-level perceptions.  The influence of subjective norms was found to have less impact than **attitudes towards the behavior** - which are specified in terms of valence and strength.  Though unstated, I would assume that the importance of subjective norms would increase for individuals with higher need for social validation.  

$$ \Large {A \propto \sum_{i=1}^n b_i e_i} $$

This Attitude model, mathematically stated (and in a process similar to probability weighting), combines a “strength of each salient belief” measurement ($b_i$) multiplicatively with a “subjective evaluation of the belief’s attributes” ($e_i$).  This process occurs for each of $n$ salient beliefs regarding an action, all of which are summed.  The final result (called a “summative belief index”) is directly proportional to a person’s attitude ($A$) regarding a specific behavior.  Interestingly, the model allows for $b$ and $e$ measurements to be either unipolar or bipolar (see p. 193), depending on theoretical justification, through the use of a simple linear adjustment.  

$$ \Large {SN  \propto \sum_{i=1}^n n_i m_i} $$

Similar to the Attitude model, the Subjective Norm (<span>$SN$</span>) model combines a bipolar measure of normative beliefs (<span>$n_i$</span>) multiplicatively with a unipolar measure of “motivation to comply” (<span>$m_i$</span>), across <span>$n$</span> salient normative beliefs.  

$$\Large {PBC  \propto \sum_{i=1}^n c_i p_i
}$$

Finally, the Perception of Behavioral Control (<span>$PBC$</span>) model multiplicatively combines control belief (<span>$c_i$</span>) with the perceived power (<span>$p_i$</span>) of each control belief, again across <span>$n$</span> control beliefs.  Control beliefs deal with the belief an individual has regarding necessary resources and opportunities.  The power of each control belief can be either positive (facilitatory) or negative (inhibitory).

All three elements (<span>$A$</span>,<span>$SN$</span>,<span>$PBC$</span>) can be summed for a “measure of the overall behavior disposition.”

## Application
The model has obvious applications for quantitatively modeling behavior probabilities.  Additionally, this paper does a good job of setting forth and clearly explaining a quantitative model, with its respective elements.