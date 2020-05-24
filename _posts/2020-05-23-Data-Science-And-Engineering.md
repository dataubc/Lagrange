---
layout: post
title: "Knowing your data"
author: "Mohammed Salama"
categories: journal
tags: [documentation,sample]
image: big.jpg
---

[Image by Kaml Phuc, via Flicker.com (Creative Commons License)](https://iabcphiladelphia.org/10-ways-to-turn-social-media-data-into-smart-data/)

During my time as a master of data science student at the University of British Columbia, I learn a wide range of tools and techniques to help extract knowledge from data, however, there was always emphasis about "knowing your data" as the most crucial step in this process.

The approach we take to deal with data and the type of the model we build will always depend on the nautre of the data. For example, let us say you are doing an Exploratory Data Analysis to data from a domain of knowledge that you know little about, the first thing you encounter before running any type of analysis is to handle the missing data. There are many techniques of filling missing data depending on the nature of the feature that contains the missing data and whether its nominal, ordinal, or numerical. For example, If it's a numerical feature, you could replace the missing the data with the mean of values in that column, perhaps you need more robust estimator such as the median if you think that outlier has a significant effect. Even the definition of an outlier depends on the knowledge domain. Is this an outlier, should we drop it, maybe not as it could add value to the analysis. You could also replace the value in a specific a row with the value of in the next row or the previous row, which option of these you choose depends a great deal on the data itself. Is it a time-series data? sensor measurements? etc.

As we proceed further in the life cycle of data analysis, the importance of "knowing" the data becomes even more important. You could be building a model that could give high accuracy but makes little sense for the practitioners. Maybe you created a neural network model with many layers sophisticated that works perfectly as black-box, while what needed was a more interpretable model such as a linear regression model.

For many professionals who are study data science to change it is imperative to understand that data science is only a tool and it only create magics when used correctly. To use it correctly means to seek to understand the data by talking to domain experts. If this is totally new field of study to you, maybe reading about the data, taking some courses, internships or mentorships. By admitting that we need more than data science to shift career we will have a smoother transition.

To summarize, data science is magnificent, It provides valuable tools and an improved way of thinking about problems when integrated with the minimum viable domain knowledge.




