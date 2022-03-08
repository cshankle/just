# 20 Years of More SMCM Data than You Could Possibly Want
### Name

## Introduction

Through my data exploration, I really wanted to look at change at St. Mary's throughout the 20 year period. I've gotten to know SMCM in a very strange time period - to understate it. By examining this data, I hoped to start to see the general arc of culture at St. Mary's. Although I didn't go to in depth to this for my data exploration, one interesting aspect of the data was the student life section. In this section, it listed major involvements that college campuses might offer and whether we had them. Seeing how these changed throughout the 20 year period was very interesting. 

My other interest in this data came from my work with the Admission Office. In the office, we think a lot about who we are attracting to the college, growing our student body, and retaining students. By exploring demographics, retention, and cost throughout the 20 year period of time, we can find patterns and see where it is better to focus time and energy.

## Dataset

I found this data on the SMCM page for institutional research under the tab Common Data Set. The college collects data about student body and faculty every year then releases it to the public on the institutional research part of the school website. They have been collecting this data since 2002, so it offers up a pretty nice picture of modern SMCM history. The Office of Institutional Research tracks this data to make improvements and to see how we are doing as a school. In its original form, the data is formatted as a pdf with all of the information for that school year. Because of this, I had to transcribe all of the data into an excel spreadsheet in order to work with it.

Links to my data:
* [Original data](https://www.smcm.edu/ir/about-st-marys/common-data-set/)
* [Cleaned up data](https://github.com/cshankle/just/blob/main/SMCM.xlsx)


## Initial Questions

I knew that I wanted to look at data about my school, so then it was a matter of figuring out which dataset would be the most interesting to look at. I chose the common data set over other datasets because it looked at more fields and it was the raw data. Other data sets had already been analyzed. When looking at the data, I was most curious about how different demographics have shifted over the years and about how cost has changed. Some questions that I had initially were:
- How has the makeup of the faculty changed in this time period?
    - Is the faculty more diverse?
    - Are there more women faculty?
- How does the makeup of the student body compare to the makeup of the faculty?
    - Are the two proportional?
- Can we track enrollment to total student body population? In otherwords, does the number of students that we attract each year correlate to changes in the whole population?

I didn't find a lot of the numbers very surprising in the data. I've gotten a pretty accurate picture of our student body through my work at the Office of Admission, so I knew what to expect in terms of student body demographics. However, I did find the consistently low number of underrepresented faculty  surprising. I was also surprised by how the undergraduate population and yearly enrollment numbers changed because that info contradicted what faculty members at the school have told me. I was a little surprised by the fact that they do not collect data about sexuality and other LGBTQ+ data points. 

I definitely had to wrangle the data since it didn't come in a usable format. This was fun as it allowed me to choose the fields to keep. There are some other notes as well:
- There were two school years in which the school didn't collect data. Because of this, there is often a break in my graphs where tableau couldn't extrapolate the info. These years were 2003-2004 and 2004-2005.
- The school combined Asian and Hawaiian, Pacific Islander and didn't include Two or more races as an option until the 2010-2011 school year. This impacts the numbers and probably contributes to a greater number of unknown responses. 
- There were a few  years in which the school didn't have data on tuition costs, so there is another break in the graphs there.
  
## Discoveries & Insights

### Basic Facts: Cost and Overall Enrollment Stats
 <img src ="https://cshankle.github.io/just/hw4/in%20state%20and%20out%20of%20state%20costs.PNG" width = "750" height = "600" > <br>
 This graph depicts the scatter plots of In State Tuition and Out of State Tuition together. I chose to plot the two together to compare how the prices have changed over the years. In State Tuition has remained cheaper than Out of State Tuition since 2001. In addition, Out of State Tuition has increased at a faster rate than In State Tuition.
 
 <img src ="https://cshankle.github.io/just/hw4/enroll%20vs%20total.PNG" width = "750" height = "600" >
 This chart plots the total number of students compared with the number of students enrolled that year. This highlights how yearly enrollment numbers have changed over the period of 20 years and how the total student body has changed over the period of 20 years. This highlights an interesting fact. While the total student body grew then started to decline, the enrollment rate declined slightly during the 20 year period and in the most recent year grew to its highest rate for the whole period. This suggests that our student body is shrinking because we aren't retaining students rather than our ability to attract students.

### Dive into Student Demographics
 <img src ="https://cshankle.github.io/just/hw4/sheet1.PNG" width = "750" height = "600" > <br>
 This bar chart shows the makeup of the SMCM undergraduate population between the years 2001 and 2020.  This chart gives an overview of all of the racial and ethnic demographics at the school, but doesn't allow us to see significant details yet. What is clear though, is that the student body is predominantly white. The second most populous portion of the student body are Black students. 

 <img src ="https://cshankle.github.io/just/hw4/proportion%20of%20students.PNG" width = "750" height = "600" > <br>
 This chart solves the problem that we encountered with the first chart. Although we could see that there were significantly more white students than students of underrepresented groups at SMCM, we couldn't see how the proportions changed over time as compared to the whole student body. This graph compares the percentage of white students to the percentage of students who are part of underrepresented groups. From this chart, we can see that the percentage of white students has been decreasing slowly since the early 2000s as the proportion of students of underrepresented groups has grown.
 
### Faculty Demographics
 <img src ="https://cshankle.github.io/just/hw4/faculty%20underrepresented.PNG" width = "750" height = "600" > <br>
 This chart compares the composition of Faculty each year. It shows the proportion white faculty and faculty who are part of underrepresented groups to the total number of faculty for that year. This chart shows that there is a small number of underrepresented faculty members and that that number has remained pretty steady.
 
 <img src ="https://cshankle.github.io/just/hw4/percent%20faculty%20underrepresented.PNG" width = "750" height = "600" > <br>
 This chart shows the proportion of SMCM faculty members who are part of underrepresented groups compared to white faculty members. It is presented as a decimal out of 1 or as a percent. The chart shows that there has not been a significant increase in underrepresented faculty members and that the number of underrepresented faculty members has not risen above 20% in the 20 years of tracking. One thing to note is that there were a few years where this data was not tracked.
 
### Student and Faculty Demographics compared
 <img src ="https://cshankle.github.io/just/hw4/underrep%20compared%20to%20underrep.PNG" width = "750" height = "600" > <br>
 This chart compares the proportion of underrepresented students to the total undergraduate body with the proportion of underrepresented faculty to the total number of faculty. The chart shows that while there has been growth among the student population, the proportion of faculty has changed very little throughout the years. It is also much lower than the student proportion, which is not ideal.
 
 <img src ="https://cshankle.github.io/just/hw4/underrep%20with%201.PNG" width = "750" height = "600" > <br>
 This chart compares the proportion of underrepresented students to the total undergraduate body with the proportion of underrepresented faculty to the total number of faculty. The chart shows that while there has been growth among the student population, the proportion of faculty has changed very little throughout the years. It is also much lower than the student proportion, which is not ideal. This chart changes the scale of the verticle axis to 1 to provide more scale.

### Dive into Student Gender Stats
 <img src ="https://cshankle.github.io/just/hw4/undergraduate%20gender.PNG" width = "750" height = "600" > <br>
 This graph shows the change in the gender makeup of the SMCM Undergraduate population. The graph is based off the data of full time students. This means it excludes part time students from the data. Less men than women attend SMCM, but the lines show similar trends of growth and decline.
 
### Faculty Gender Stats
 <img src ="https://cshankle.github.io/just/hw4/Faculty%20Gender.PNG" width = "750" height = "600" > <br>
 This graph shows how the gender makeup of faculty at SMCM has changed since 2001. The orange line represents women faculty members while the blue line represents men faculty members. Until 2018, there were more men faculty members than women faculty members. In 2018, the trend changed and there were more women faculty than men. This reflects the gender composition of the student body better than previously, since there are more women than men at SMCM.
 
### Student and Faculty Gender Stats Compared
 <img src ="https://cshankle.github.io/just/hw4/women%20comparison.PNG" width = "750" height = "600" > <br>
 This chart plots the proportion of Full-time women undergraduate students to total undergraduate students along with the proportion of women faculty members to total faculty members. In the chart, we can see that women faculty members make up a smaller percentage of faculty than women students in the student body. We can also see that both populations increased in comparison to their total populations.
 
## Conclusion
I thought this project was very interesting and that it shed new light on our school's recent history. While the growth of underrepresented group in the student body has been significant, there needs to be more work for the faculty to accurately represent the population. If I continued this project, I would want to look at other aspects of the school history then match these data points to those. I would also want to take a general Maryland census data set and compare our numbers/demographics to those of the whole state.

## Sources
- [smcm school website](https://www.smcm.edu/ir/)
