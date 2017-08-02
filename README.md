# election-maps
Maps about the 2017 B.C. Election

Using the methods described in [https://medium.com/@mbostock/command-line-cartography-part-1-897aa8f8ca2c] (Mike Bostock's "Command Line Cartography" series) to build B.C. election maps
The goal is to understand how support for each party changed across the province

[https://docs.google.com/spreadsheets/d/1BoXEyhiTEbutXLmRyZGp5_9xoDivzuI0TA4NBjvfWdY/edit?usp=sharing] (Vote Data for Comparisons)

shape data for making the maps are at https://catalogue.data.gov.bc.ca/dataset/current-provincial-electoral-districts-of-british-columbia (edited)


B.C. elections data are at http://elections.bc.ca/resources/voting-results/provincial-general-elections-results/ (edited)

important note re: making maps from data available on B.C. open data site - they're already pre-projected, but we still need to modify the geometry from meters to pixels
https://medium.com/@mbostock/your-data-is-already-projected-so-the-simplest-thing-to-do-is-to-use-the-existing-projection-86cb49a9a923

several ridings have changed names and shifted since 2013, which needs mentioning in a caption
