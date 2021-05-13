# Coronavirus twitter analysis

This repository analyzes the use of the conora hastag on twitter, along other hashtags realted to the COVID-19 pandemic. There are three programs in this repository (stored in the src folder) that are used to create a final vizualization of the number of times each COVID-19 related hashtag is used in a tweet: 

1. map.py: This program processes all the .zip files in a given --input-path. The program first extracts the .zip file and then proceeds to create a corresponding  .lang and .country file. These files are saved to the output folder. 
2. reduce.py: This program takes all the .lang and .country files from the output folder and merges them into a reduced.lang and a reduced.country file, respectively. 
3. vizualize.py: This program take in the reduced files as well as a key, which is a string represnting the hashtag that will be searched for. The program then outputs a file for each given hashtag into the viz folder. 

The resulting files in the viz folder can be viewed to see the counts of the COVID-19 related hashtag used on twitter. This process can be completed to see the counts for any other hashtag as well!
