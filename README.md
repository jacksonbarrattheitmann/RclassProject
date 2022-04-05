# RclassProject

Raw Data and Meta Data is located on Google Sheets link below
https://docs.google.com/spreadsheets/d/1LGUmCvF7xY7p0qE6nsZWLhl1dX86EEfllkQDXjw5CJ8/edit#gid=0

You will find the first dataset used is the very first sheet named "bird_data".

The second dataset used is in the "just_wet_attribute" sheet tab.

The meta data is under the "meta_data" sheet tab.

Objective of Project

To determine what vegetation charecteristics of ephemeral wetlands drive avian biodiversity. 

Codebase Notes

I've got quite a few notes about utilizing the code in the Rmd file with all of the source code. But, a few
things to be aware of. I needed to reformat my "raw_data" sheet into a community matrix in order to perform 
some of my statistics. So my first code chunk in the Rmd is really just massaging the data to get the metrics
I need. 

Then, in my second code chunk, I needed to do soem manual column construction in google sheets, which I probably coud have done in R...
But, it was a lot easier to match up wetland_id with the respective shan_sr score. 
