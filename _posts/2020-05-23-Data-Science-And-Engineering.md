---
layout: post
title: "Are you changing career to data science"
author: "Mohammed Salama"
categories: journal
tags: [documentation,sample]
image: big.jpg
---

[Image by Kaml Phuc, via Flicker.com (Creative Commons License)](https://iabcphiladelphia.org/10-ways-to-turn-social-media-data-into-smart-data/)

It is not unusual to read posts with titles such as " How I moved from engineering to data science" or " How I changed my career from finance to data science". However, I want to argue that data science is not a job /career, and rather it is a way of thinking, a tool and technology.

During my time as a master of data science student at the University of British Columbia, I learn a wide range of tools and techniques to help extract knowledge from data, however, there was always emphasis about the domain knowledge.  This is important because data science does not live in a vacuum, you need the data to apply..well the science! you have to apply it to a field of study, finance, medicine, sales and marketing, engineering, etc. 
For example, let us say you are doing an Exploratory Data Analysis to data from a domain of knowledge that you know little about, the first thing you encounter before running any type of analysis is to handle the missing data. There are many techniques of filling missing data depending on the nature of the feature that contains the missing data and whether its nominal, ordinal, or numerical. For example, If it's a numerical feature, you could replace the missing the data with the mean of values in that column, perhaps you need more robust estimator such as the median if you think that outlier has a significant effect. Even the definition of an outlier depends on the knowledge domain. Is this an outlier, should we drop it, maybe not as it could add value to the analysis. You could also replace the value in a specific a row with the value of in the next row or the previous row, which option of these you choose depends a great deal on the data itself. Is it a time-series data? sensor measurements? etc.

As we proceed further in the life cycle of data analysis, the importance of "knowing" the data becomes even more important. You could be building a model that could give high accuracy but makes little sense for the practitioners. Maybe you created a neural network model with many layers sophisticated that works perfectly as black-box, while what needed was a more interpretable model such as a linear regression model.

Does that mean you can not "change" career from one field to another as a result of learning data science? Of course, you can and I can think of at least two ways to do this. The first is to specialize in developing tools that help data scientist by building a more efficient algorithm, creating libraries and packages etc. The second way is to do shift career to a different field of study but first by learning about this new field, perhaps by reading some books, taking some courses, internships or mentorships. By admitting that we need more than data science to shift career we will have a smoother transition.

To summarize, data science will never replace domain knowledge. It provides valuable tools and an improved way of thinking about problems when integrated with the minimum viable domain knowledge.




