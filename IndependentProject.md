HIMB Summer Course - Remote Sensing Independent Project
================
Carly Portch
2019-05-31

## R Markdown information

\#(remove this section once you no longer need this
information)

<!-- This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>. -->

<!-- When you click the **Knit** button, a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this: -->

<!-- ```{r cars} -->

<!-- summary(cars) -->

<!-- ``` -->

<!-- Try pressing the **Knit** button now to see what this looks like. -->

<!-- ```{r setup, include=FALSE} -->

<!-- # This is the 'setup' code chunk that tells the document whether to include anything from your code chunks in the output (knitted) document. "include=FALSE"" says "don't include code in my output". -->

<!-- # You can also load R packages here. I've added the tidyverse package already since it's very useful, and you can insert here any other packages you eventually need for your analyses. -->

<!-- library(tidyverse) -->

<!-- ``` -->

<!-- Here is a 'cheat sheet' for how to format text in RMarkdown (e.g., how to make headings, bold text, italics, bulleted/numbered lists, etc.): -->

<!-- https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf -->

## Summary

The goal of this study is to understand the sediment transport systems
at Torbay in Albany, Western Australia. Due to the site’s large waves
and rugged coastline, it undergoes significant erosion and deposition
annnually.

## Question(s)

Listed below is the specific, testable question my project seeks to
answer:

Is there quantifiable seasonal variability of sediment transport along
the Torbay coastline through satellite
imagery?

## Introduction

<!-- #Insert here some brief (2-3 sentence) background information on your project (e.g., what the current state of knowledge is on the topic, why your question(s) need to be answered, etc.). -->

Torbay is a large Southern-facing bay situated along the Southern Ocean.
It is known for its large swell, with average wave heights of 2-3 m and
extreme wave heights of 8-10 m during storms. The nearshore zone
consists of a rocky fringing reef with various pockets of sand,
explaining it’s well known term “sandpatches”.

Torbaay has been selected as a testing facility for wave energy
companies to trial a commercial-scale wave energy farm, however there is
currently very limited knowledge on the existing conditions of the site.
In order to understand the potential coastal impacts of these wave
energy farms, it is important to first understand what the natural,
seasonal variations
are.

## Methods

<!-- #Insert here a few sentences and/or dot points to briefly summarize the methods you're using. Include any details you'd need to know if coming back to this project at a later date when you might not remember exactly what you did this week.  -->

  - Select a location of interest within Torbay (i.e. a sand patch that
    has annual sediment change)
  - Look through google earth and screenshot all available photos and
    identify dates associated
  - Do the same process for the Planet data for a one year time period.
    Pick the best (most visible) photo from each month at the same
    location of interest as selected for the Google Earth images.
  - Quantify each photo as sandy or rocky on a scale of 1 (being sandy)
    to 10 (being rocky) to See if there are any seasonal patterns
    (i.e. winter rocky, summer sandy)
  - If a trend emerges, pick another location along the Torbay coast and
    repeat method to see if the same results occur. If not, there may be
    longshore sediment transport that must be taken into account.
  - Identify any visible plumes of sediment, dark patches, and/or rip
    currents in the selected photos to see if it aligns with the
    identified
patterns.

<!-- #You can embed images (e.g., maps, diagrams, screenshots, etc.) by using the following code: -->

<!-- #Images on the web:  -->

<!-- #![optional caption text](https://www.bestfunnies.com/wp-content/uploads/2012/08/Funny-Fish-11.jpg) -->

<!-- #To add images from your local files that are stored in the same directory (folder) as your Rproject, replace the web address above with the fliename of your image. -->

## Results

<!-- #Summarize the current status of the project - i.e., how far you got in your data collection, what's left to do, any patterns you've noticed so far. etc.  -->

<!-- Once you've collected your data, this is where you'll do your R plotting and analyses.  -->

<!-- You can embed plots in this section, for example (replace this with your own when you're ready to make plots): -->

<!-- ```{r pressure plot, echo=FALSE} -->

<!-- plot(pressure) -->

<!-- ``` -->

<!-- (Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot, but this can be changed if, for example, you want to share both your code and your plots with collaborators in early stages of a manuscript.) -->

<!-- You would also do your analyses in this section, and you can choose whether or not your code and analytical results show up in the output (knitted) document, for example (replace this with your own when you're ready to do analyses): -->

Thus far in my analysis, I have gone through all available Google Earth
images of a selected location, and all of the Planet data for 2017. I
created the table below to summarize the results I have so far:

(See “Project Data Analysis.xlsx” for table).

Below are two sample photos from Google Earth showing the location in
winter vs summer:

![February 2017 - Google Earth](Images/20170223.png)

![October 2017 - Google
Earth](Images/20161021.png)

<!-- ```{r pressure analysis, echo=TRUE} -->

<!-- model <- lm(pressure~temperature, data = pressure) -->

<!-- summary(model) -->

<!-- ``` -->

## Discussion

<!-- #insert here a few sentences about anything you've learned so far - e.g., any unexpected patterns, any challenges you've had, next steps, etc. -->

It is clear that there is a trend between the summer/fall and
winter/spring seasons. It appears that it is very sandy in the summer
and fall (aka sand is being deposited back on shore when waves are
small), and rocky in winter (aka harsh waves are eroding the beach, and
taking sand offshore).

A secondary goal of this study was to try and identify whether it was
possible to use Planet data (since it provides daily data) to draw
conclusions as to the condition of the beach (eroded or deposited), or
if it was best to do our own field survey, or use Google Earth (very
clear data, but only approx. 2 photos per year). It was evident that
some results can be pulled from Planet as a way to get an initial idea
of the trends (i.e. the trends I’ve identified), but then to get the
more specific details (i.e. cross shore vs longshore transport, and the
quantitative amount of sand being moved each season etc.), it may be
necessary to conduct a field study. This also helps with setting up the
field study and planning out the times of the year that will likely give
the most contrasting results (i.e. Feb vs Nov).

## References

You won’t likely need this section at this stage, but when you’re
writing a paper, can insert references into RMardown docs - see
<https://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html>.
