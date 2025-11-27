# Chem-274B-Micropresentation
This project will use graph-based analysis to find correlations between different health states, treatments, and diseases. This would be with the purpose of finding specific patterns of use for whatever is needed by the user.

## Definitions

We need to define certain terms so that we can properly understand how the program works, and how to use it: 

Health State - This includes symptoms, conditions, and any state that can be defined medically (i.e. nausea, pain, sadness, etc.)

Treatment - This includes medications and therapies that can be used to help modulate health states (increase or decrease symptoms, etc.) and are used in response to either health states or diseases

Disease - This is something that has a cause, health states, and potential treatments. However, they're not necessary (COVID can sometimes be asymptomatic, which I guess in itself could be a health state)

## What this program should do

Using networkx:

- This program should be able to input data, and all the related attributes
- It should be able to create an edge between two attributes after already inputing the data (and remove it)
- It should be able to find some correlations after the fact related to some or multiple attributes
- It should be able to make visualizations

## Specific questions

- How should the data be input into the graph? Will we store the attribute and the description as a tuple? 
- How are the correlations going to happen? What kind of correlations are we expecting to find? What algorithms already exist that we can utilize? 
- Where are we going to find data from? I'm sure this kind of data can't be too hard to find, but we have to find it