# CovQuA: A Covid Question Answering Machine
This project was for the course CS 6120: Natural Language Processing. The team that worked on this project included Aislin Black, Akanksha Agnihotri, Divyangana Pandey, Ashish Jeldi

## Problem Statement
With the explosion of Large Language Models (LLMs) over the past few years, many downstream tasks have been performed using these models. One such task is the Question-ANswering Task, where given a particular question and context, the model produces answer to the question. Such models incorporate semantic indexing of words given a context and try to discover the different ways a word can be represented as per the context. 

Ever since the pandemic began in 2020, there has been an overflow of information about Covid.
Research papers, news articles, health magazines, online portals like WebMd, WHO's official
website is flooded. However, these articles are hardly read entirely by the common public. We
heavily rely on web searching for questions like “Common symptoms for Covid”, “Nearest test
center around me” etc. This project aims to build and evaluate the commonly available LLMs : GPT, BERt and ALBERT at answering questions related to COVID pandemic.

## Tools
Python, Jupyter Notebook, HuggingFace Transformers

## Dataset
We use the Stanford Question and Answering Dataset (SQuAD) found [here](https://rajpurkar.github.io/SQuAD-explorer/ ). The Stanford Question and Answering
Dataset (SQuAD) is a dataset of question and answering pairs.  It is widely used for question and
answering models because the answer to each question is a segment of text from its
corresponding context passage. SQuAD is widely used because of its size and its complexity.

