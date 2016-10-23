# MATLAB Fall 2016 – Research Plan 


> * Group Name: First-mover advantage research group
> * Group participants names: Jonathan Orsinger,Pierre-Yves Savioz,M. Asfandyar Sheikh
> * Project Title: First-Mover Advantage in Scientific Publications

## General Introduction

Among scientific publications, a first-mover advantage is observable. This means that the impact and number of citations of a scientific paper are largely dependent on the time of publication. E.g. the first paper to be released in a specific field is more likely to be cited more often than a paper which is published later, regardless of the quality of these. This could lead to the conclusion that it may be better to publish a mediocre paper at an earlier time rather than an excellent one at a later time. This could result in a long term problem for the future of science.

## The Model

The resources mentioned in "References" below will be used to implement a simulation of the first-mover advantage in MATLAB. A basic model is already proposed by M.E.J. Newman in his paper [1], which is based on the fact that the probability for a paper to be cited is proportional to the number of citations it already has. This leads to a power law which describes the influence of the time a paper is published on the number of citations it will eventually receive. Thanks to this law we can compare the occurrence of the phenomenon in various scientific fields and research on the reasons a why it may be more prominent in certain ones.

## Fundamental Questions

Comparing, the data to the theoretical predictions will allow us to determine in which fields the first-mover advantage is more observable than in others. This may have certain causes which can be dependent or independent on the specific field or can be due to general reasons. Basically, our project can be focused on two research questions:

- In which scientific fields can the first-mover advantage be observed?
- Why is the first-mover advantage predominant in certain fields as opposed to others? Considering the second proposed question, we would like to focus on certain fields which are relevant to our degree programs and that are new enough for comprehensive data to be found (e.g. gravitational waves).


## Expected Results

We expect that the theoretical predictions of the model will fit the data quite well in certain scientific fields, as shown in Newman's paper [1]. However, we are aware that not every scientific field will deliver so good results. We will then have to find an explanation to this difference between the data and the predictions. They can be for example due to cross-citations between the field in question and other ones or to the lack of data which is old enough to cover the whole history of the field. For example, it will be almost impossible to notice the first-mover effect in fields such as astronomy, in which documents were written long before scientific magazines or papers, which are the only ressources we will base our research on.


## References 

Basically, two kinds of resources are available, currently, to analyze the problem described above:

Scientific papers:
- [1] NEWMAN M.E.J., The first-mover advantage in scientific publication, 25th June 2009
- [2] LIEBERMANN M.B., MONTGOMERY D.B., First-Mover Advantage, Strategic Management Journal, Vol. 9, 41-58 (1988)

Data regarding the number of citations that papers received over the years.

We will use different resources to implement our model. Additional resources may be used to answer our further research questions.


## Research Methods

In his paper, M.E.J. Newman proposed a model he developed theorically to find the power law mentioned above. However, he suggested that the same model could be simulated using numerical methods. This is basically what we intend to implement on MATLAB.


## Other

(mention datasets you are going to use)
