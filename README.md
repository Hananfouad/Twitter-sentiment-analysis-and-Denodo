# Twitter-sentiment-analysis-and-Denodo

This document explains how to integrate Twitter with Denodo and how to use sentiment analysis libraries to classify tweets according to information contained in the text of the tweets.

Sentiment analysis refers to the use of natural language processing techniques to extract subjective information from texts.

These techniques can be used to determine the attitude of a speaker regarding some topic or the overall contextual polarity of a text.
There are multiple libraries available to perform sentiment analysis in Java such as Gate,  OpenNLP, Lingpipe, among others.


In this article we will use LingPipe as an example for several reasons but any other Java library could be easily integrated with Denodo:


LingPipe is open-source (not free for commercial purposes).
It implements many of the most popular POS (Part-Of-Speech) tagging, NER (Named Entity Recognition) and classification algorithms.
LingPipe will just classify the tweets into positive, negative or neutral.

An easy way to apply sentiment analysis within Denodo is by creating a custom function that, using a sentiment analysis library, returns the results coming from the library when a specific text is passed as input.

In this project we will explain how to create a custom function to classify tweets coming from a JSON data source using the Twitter API.

1. Creating a custom function
2. we need to import the following libraries jar files from the LingPipe distribution: ● lingpipe-4.1.0.jar ● log4j.jar
3. Export the project
4.	Import Extensions in Denodo
5.	Test
6.	Create a JSON Datasource
7.	Connecting Denodo with Twitter
8.	Create a base view
9.	Create a flatten view
 












