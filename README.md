### tableau_citibike


## Description
The purpose of this project was to investigate the impact of the COVID-19 pandemic on New York City's Citibike ride sharing service.  In order to do this, I aggregated data from the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage from January 2020 through November 2020, cleaned and analyzed the data for roughly 19 million rides, and then built a Tableau Story to provide a narrative that would help explain the impact of the pandemic on the Citibike program.  The Tableau Story includes two interactive dashboards so that users can further explore the data.

This Belly Button Plot.ly project creates an interactive dashboard that allows the user to analyze the microbial portrait of each test's subject navel (belly button).  In 2011, the Public Science Lab at NC State began a study into the microbes that inhabit the human belly button, and the data supplied for this dashboard came directly out of that study.

![B3](https://github.com/loucksjohn/tableau_citibike/blob/main/images/citibike-new.jpg?raw=true)


## Operating Instructions
In order to view the Tableau story and dashboards, you can either download the 'citibike.jl.twb' file in this repo and view in your Tableau desktop app or you can also access it online by visiting my [Tableau Public](https://public.tableau.com/profile/john.loucks5224#!/vizhome/CitiBikeStory_16116200207080/CitiBikeStory) account.  In the top right-hand corner of all the views, there are sliders that allow you to view the entire eleven month timeframe or drill down into specific months.

## Resources
In the GitHub repository for this project you will find all the resources necessary for the creation of this dashboard.  Here's a quick rundow of those files and a brief explanation:
* samples.json - the Belly Button Data Set from the Public Science Lab that contains all of the information regarding the individuals who participated in the study and the bacteria found in their belly button
* index.html - is the the webpage framework that displays the interactive dashboard in the browser
    * please note that within the index.html file you will find addtional outside sources.  Bootstrap is being referenced in the building of the webpage structure, D3 is being used as a source to manipulate the data in the files , and plot.ly is also being used as a source to help create the charts/graphs.


##  Final Analysis
It comes as no surprise to report that the Covid19 pandemic had significant impact on CitiBike ridership during 2020.  Prior to downloading and analyzing the data, I knew the effects of the pandemic would have a negative impact on the program--but I was unsure as to what the final analysis would show.  Here are the main three  phenomena that are most important and deserve to be pointed out:

#1 --  When the lockdown began in late March, as expected, the number of total rides decreased dramatically--even as the weather was warming and becoming more conducive to bike travel.  What wasnt't expected was the dramatic shift away from the typically busiest start stations in Mid-Town, Chelsea, NYU, etc to a much more decentralized dispersement.

#2--The second phenomenon that was discovered via analysis of the data, which was maybe a little bit easier to anticipate, was the big decline we saw in the 8am hour for starttimes.  With lockdown causing businesses and schools to close, we see how important those morning rush hour riders are to our overall numbers.   As restrictions started to ease and re-opening phases began--we see overall ridership increase, especally for that morning rush hour.  We should consider incentivizing those morning rush hour riders to come back now that they've maybe they're still not having to go into the office or classroom, or have found alternate methods for getting to where their going in the morning.  At the very least we should do a campaign educating the public about how the bikes are cleaned and that they are safe.

#3--The Final phenomenon to address is that we are still having a significant percentage of riders fall into the "unknown" gender category.  Since we're always striving for better user data so that we can more precisely tailor our maketing campaings, I think we should institute so minor changes to see if we can convert some of those "unknown" riders into a category.  And what I am suggesting is to increase the number of "gender" categories from just two (male & female).  Some riders may feel those categories too gender binary and in an effort to be more inclusive we could add several gender-neutral designations.  This is a topic that could be further investigated in order to provide some good options to be added to the possible selections.
## Author
John Loucks\
Email:  johnloucks@gmail.com\
GitHub:  https://github.com/loucksjohn





https://public.tableau.com/profile/john.loucks5224#!/vizhome/CitiBikeStory_16116200207080/CitiBikeStory