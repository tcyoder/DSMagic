# DSMagic
Final Project for MIS 5470


Using Data Science to Create Disney Magic - Introduction
=======================================================

If you’re like me, you visited Walt Disney World every year growing up with your family. Every single year. You’re probably not like me though, which is normal. There are an abundance of services that help you plan your trips, but one has always stood out - Touring Plans dot com. Their crowd calendars and daily plans based on attraction wait times are incredibly accurate and efficient. As it turns out, their team is made up of data scientists who also somehow ended up as ‘Disney People’.

Article from Popular Science about the site - https://www.popsci.com/touring-plan-app-disney-lines

Inspired by the site and armed with some new programming knowledge, let's use R dive into the data sets provided to try and predict days where we can expect a posted wait time of 15 minutes or less at Spaceship Earth. It’s not Disney magic, it’s Data Science!


Goal of the Project
-------------------

The goal of this project was to perform an analyis of the datasets provided by the good folks at Touring Plans. After digging in I eventually decided to focus on predicting posted wait times under 15 minutes for the attraction 'Spaceship Earth' at EPCOT. My personal goal was to reinforce the techniques we learned in class and hopefully be forced to expand beyond that. I felt less comfortable with R than with Python so I have focused this project on using R. I have tried to develop my R Markdown files similar to the notes we ran through in class so that the project is easy to follow.

Working Through the Project
---------------------------

The root folder 'Yoder_DS_Magic' contains all of my R markdown files as well as the Rproj file. The data is all in the 'Data' folder and all images are in the 'Images' folder. All the completed HTML files can be found in the folder 'Completed HTML Files'. The HTML files provide the cleanest and quickest read through. I have numbered the HTML files in the order I completed them. All of my files can also be found on GitHub - https://github.com/tcyoder/DSMagic 

Lessons Learned
---------------

After seeing the results of the models I created, I did not get the results that I expected. My feeling is that I needed to spend WAY MORE time doing EDA. I do not believe my chosen predicative variables were very strong and I needed to feature engineer some better ones. I wanted to push myself using a dataset we had not worked on in class or had any Kaglle contests to reference. I ended feeling more comfortable with basic R, learning more about probability thresholds, and spending an entire day getting one KNN model. My best model of all was a random forest model with 70% accuracy. I was hoping to get some quality models out of this project but I think my lack of a solid grasp on the R language (and enough of a stastical background) held me back. I am happy I challenged myself to take this class! 

Citations
---------

The datasets were provided by Touring Plans. 

"spaceship_earth.csv", Disney World Ride Wait Time Datasets, TouringPlans.com, November 2018, https://www.touringplans.com/walt-disney-world/crowd-calendar/#DataSets, Accessed 04 November 2018.

"metadata.csv", Disney World Ride Wait Time Datasets, TouringPlans.com, November 2018, https://www.touringplans.com/walt-disney-world/crowd-calendar/#DataSets, Accessed 04 November 2018.

"touringplans_data_dictionary.xlsx", Disney World Ride Wait Time Datasets, TouringPlans.com, November 2018, https://www.touringplans.com/walt-disney-world/crowd-calendar/#DataSets, Accessed 04 November 2018.
