# 20 Years of More SMCM Data than You Could Possibly Want
### Name

## Introduction

Through my data exploration, I really wanted to look at change at St. Mary's throughout the 20 year period. I've gotten to know SMCM in a very strange time period - to understate it. By examining this data, I hoped to start to see the general arc of culture at St. Mary's. Although I didn't go to in depth to this for my data exploration, one interesting aspect of the data was the student life section. In this section, it listed major involvements that college campuses might offer and whether we had them. Seeing how these changed throughout the 20 year period was very interesting. 

My other interest in this data came from my work with the Admission Office. In the office, we think a lot about who we are attracting to the college, growing our student body, and retaining students. By exploring demographics, retention, and cost throughout the 20 year period of time, we can find patterns and see where it is better to focus time and energy.

## Dataset

I found this data on the SMCM page for institutional research under the tab Common Data Set. The college collects data about student body and faculty every year then releases it to the public on the institutional research part of the school website. They have been collecting this data since 2002, so it offers up a pretty nice picture of modern SMCM history. The Office of Institutional Research tracks this data to make improvements and to see how we are doing as a school. In its original form, the data is formatted as a pdf with all of the information for that school year. Because of this, I had to transcribe all of the data into an excel spreadsheet in order to work with it.

Links to my data:
* [Original Data] (https://www.smcm.edu/ir/about-st-marys/common-data-set/)
* [Cleaned up Data] (https://github.com/cshankle/just/blob/main/SMCM.xlsx)


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
 <img src ="https://cshankle.github.io/just/hw4/enroll%20vs%20total.PNG" width = "750" height = "600" >

### Dive into Student Demographics
 <img src ="https://cshankle.github.io/just/hw4/sheet1.PNG" width = "750" height = "600" > <br>
 <img src ="https://cshankle.github.io/just/hw4/proportion%20of%20students.PNG" width = "750" height = "600" > <br>
### Faculty Demographics
 <img src ="https://cshankle.github.io/just/hw4/faculty%20underrepresented.PNG" width = "750" height = "600" > <br>
 <img src ="https://cshankle.github.io/just/hw4/percent%20faculty%20underrepresented.PNG" width = "750" height = "600" > <br>
### Student and Faculty Demographics compared
 <img src ="https://cshankle.github.io/just/hw4/underrep%20compared%20to%20underrep.PNG" width = "750" height = "600" > <br>
 <img src ="https://cshankle.github.io/just/hw4/underrep%20with%201.PNG" width = "750" height = "600" > <br>

### Dive into Student Gender Stats
 <img src ="https://cshankle.github.io/just/hw4/undergraduate%20gender.PNG" width = "750" height = "600" > <br>
### Faculty Gender Stats
 <img src ="https://cshankle.github.io/just/hw4/Faculty%20Gender.PNG" width = "750" height = "600" > <br>
### Student and Faculty Gender Stats Compared
 <img src ="https://cshankle.github.io/just/hw4/women%20comparison.PNG" width = "750" height = "600" > <br>
## Conclusion
I thought this project was very interesting and that it shed new light on our school's recent history. While the growth of underrepresented group in the student body has been significant, there needs to be more work for the faculty to accurately represent the population. If I continued this project, I would want to look at other aspects of the school history then match these data points to those. I would also want to take a general Maryland census data set and compare our numbers/demographics to those of the whole state.

## Sources
- https://www.smcm.edu/ir/
