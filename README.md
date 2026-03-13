# Project compendium template

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## A compendium of code, data, and author's manuscript accompanying the manuscript:

#### TBD


## Overview

This is my Spring 2025 capstone project. I conducted qualitative analysis for a misinformation pilot study 
that created and tested experimental advertisements to counteract misinformation. A total of 594 written 
responses were collected from 99 participants, who were asked the following qualitative questions (“QQ”):

_**QQ1:** What are some reasons you think people are attracted to radical groups?_
_**QQ2:** What are some reasons you think people believe false ideas circulating online?_
_**QQ3:** Describe a situation in which supporting friends would be more important than telling the truth._

Thematic and content analysis was performed on the responses to identify common theme. Every response
was thoroughly reviewed several times, and if the meaning of a response still could not be understood after
this process, the response was placed in the “Other” category—different from the “Unsure” category, where
participants explicitly stated that they were unsure and did not have an answer for a QQ.
A composite score was also developed to measure how much a person’s response changed to each QQ, by
taking the count of words and sentences before and after an ad, normalizing the counts to make them
equivalent, adding them together, then dividing by two to produce an average score.

Normalized count of words+ Normalized count of sentences
2

In summary, participants’ views remained mostly unchanged before and after an ad, except for QQ1, which
had 9 categories (the most amount of categories for any QQ) and the largest amount of change. Additionally,
the composite score always increased whenever participants were show an audio-visual ad, whether a control
or test ad, and when the data was analyzed based on gender instead of ad group, there were slight contrasting
views in how males and females answered a question.

This repository is organized as a reproducible research compendium. There are three main sources of information: 

1. The original dataset located at analysis/data: "sketches_for_skepticism_original.xlsx"
2. A shortened version of the above mentioned dataset used for analysis in R: "lying_data.xlsx"
3. The R Studio file the produced the report:
