---
layout: default
title: "BUS204: Business Statistics"
course_description: "An introductory survey of quantitative methods (QM), or the application of statistics in the workplace. This course examines techniques for gathering, analyzing, and interpreting data across a number of fields, from anthropology to hedge fund management."
next: ../Unit07
previous: ../Unit05
---
**Unit 6: Correlation and Regression** <span id="6"></span> 
*If two data points move in the same direction, does that mean that one
causes the other? How are we to analyze their correlation?*  
  
 *Regression is an analysis of the relationship of one variable to
another. A regression might identify, for example, the relationship
between car speed and the number of fatal accidents. In this example,
speed and number of accidents are the two variables; the number of
accidents is said to be the dependent variable, because the number of
accidents depends on the speed. Speed is considered the independent
variable. While regressions can be calculated manually, a statistically
significant dataset could take a long time to regress.*  
  
 *Regressions not only allow us to determine whether a relationship
exists but also to identify how strong that relationship is. The measure
of this relationship is known as the* regression coefficient*. If the
regression coefficient is relatively low, then speed may not be the
major factor in fatal accidents. Perhaps the major factor is the time of
day, whether it rained or not, or if alcohol was involved. With multiple
regression, a number of independent variables can be tested against the
dependent variable at the same time. The regression coefficient would
determine which variables have the strongest relationship with the
dependent variable. In business, you will frequently use regression to
predict future events. Though not an exact science, regression can be
used to make reliable predictions if enough variables are
identified. For example, first responders could use regression outputs
to predict the number of fatal accidents in a given shift based on
average travel speed, time of day, weather, and any other factors deemed
significant. This unit will also stress the importance of determining
the factors that most likely contribute to a dependent variable.*  
    
 *Regression is often used in finance. Investors often want to know the
relationship between a stock’s performance and the overall performance
of the market. By regressing the period returns of a stock with the
returns of the market, investors can see the regression
coefficient. This coefficient is known as a stock’s* beta *and is
covered extensively in* [*BUS202: Principles of
Finance*](http://www.saylor.org/courses/bus202/)*.*

**Unit 6 Time Advisory**  
Completing this unit should take approximately 20 hours.   
  
 ☐   Subunit 6.1: 4.5 hours
☐   Reading: 3 hours

☐   Lecture: 1.5 hours

☐   Subunit 6.2: 4.5 hours
☐   Reading: 3.5 hours

☐   Lecture: 1 hour

☐   Subunit 6.3: 5 hours
☐   Reading: 3 hours

☐   Lecture: 2 hour

☐   Subunit 6.4: 2 hours  
  
 ☐   Subunit 6.5: 4 hours

**Unit6 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   identify the dependent and independent variables in the linear
    regression model;
-   calculate the equation of the regression line, and plot it;
-   describe the importance of the correlation coefficient and
    r-squared, and apply these concepts;
-   define *outlier*, identify examples of outliers, and describe what
    an outlier can do to summaries of data;
-   estimate a regression line, and identify the effect of the
    independent variable on the dependent variable; and
-   draw a scatterplot,explain how to use a spreadsheet to draw a
    scatterplot, find the equation of the least-squared line, and draw
    the line.

**6.1 Working with More Than One Variable** <span id="6.1"></span> 
-   **Reading: University of California, Berkeley: Philip Stark's
    *SticiGui*: “Chapter 5: Multivariate Data and Scatterplots”**
    Link: University of California, Berkeley: Philip Stark's *SticiGui*:
    [“Chapter 5: Multivariate Data and
    Scatterplots”](http://www.stat.berkeley.edu/~stark/SticiGui/Text/scatterplots.htm)
    (HTML and Java)  
        
     Instructions: Read Chapter 5 to learn how to analyze the
    relationship between two variables. Two variables may be positively
    or negatively related when different pairs of data show the same
    pattern. For example, when incomes of individuals rise so does their
    consumption of goods and services; thus, income and consumption are
    considered to be positively related. As a person’s income rises, the
    number of bus rides this person takes falls; thus, income and bus
    riding are negatively related. There are several exercises and Java
    applets embedded in the text that are meant to further reinforce
    your learning. *Do not skip these exercises!* For instructions on
    how to navigate these exercises, see “Special Instructions
    on *SticiGui *Exercises and Java Applets” in the “Course
    Information” section. This resource covers the topics outlined in
    subunits 6.1.1 to 6.1.4.   
      
     Reading this chapter should take approximately 3 hours.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: YouTube: University of California, Berkeley: Philip
    Stark's *Statistics 21*: “Lecture 4” and “Lecture 5”**
    Links: YouTube: University of California, Berkeley: Philip Stark's
    *Statistics 21*: [“Lecture
    4”](http://www.youtube.com/watch?v=HyJZcWD_1Zg&list=PLC08AC3E4790D974D&index=53&feature=plpp_video)
    (YouTube) and [“Lecture
    5”](http://www.youtube.com/watch?v=SmzEZwFvKko&list=PLC08AC3E4790D974D&index=52&feature=plpp_video)
    (YouTube)  
        
     Also available in:  
     [iTunes
    U](http://itunes.apple.com/mt/itunes-u/statistics-21-002-fall-2009/id354823031)
    (Lectures 4 and 5)  
        
     Instructions: Watch "Lecture 4" from 50:00 to the end and then
    watch “Lecture 5” from the beginning until 38:00. These videos
    complement Chapter 5, with the author of the text working through
    the materials. This resource covers the topics outlined in subunits
    6.1.1 to 6.1.4.    
      
     Watching these lectures and pausing to take notes should take
    approximately 1.5 hours.  
        
     Terms of Use: The videos above are licensed under a [Creative
    Commons Attribution-Noncommercial-No Derivative
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/). They
    are attributed to Philip Stark and the University of California. The
    original versions can be found
    [here](http://www.youtube.com/watch?v=RqIfbcgpx5w) and
    [here](http://www.youtube.com/watch?v=k6YkcX6e8OU) (YouTube). 

**6.1.1 Multivariate Data** <span id="6.1.1"></span> 
*Note: The reading and lectures assigned below subunit 6.1 cover this
topic. Pay attention to bivariate data, which is about tracking two
variables for each observation.*

**6.1.2 Scatterplots** <span id="6.1.2"></span> 
*Note: The reading and lectures assigned below subunit 6.1 cover this
topic. Note that a scatterplot usually shows the dependent variable on
the Y-axis and the independent variable on the X-axis.*

**6.1.3 Outliers** <span id="6.1.3"></span> 
*Note: The reading and lectures assigned below subunit 6.1 cover this
topic. Under the heading labeled “Describing Scatterplots,” review why
an outlier, which is an unusual value, creates problems for getting
summary statistics such as the mean.*

**6.1.4 Association** <span id="6.1.4"></span> 
*Note: The reading and lectures assigned below subunit 6.1 cover this
topic. Be sure to revisit the section labeled “Scatterplots” and note
how two variables are said to be linearly associated as their paired
values form a straight line that either moves up or down.*

**6.2 Correlation and Association** <span id="6.2"></span> 
-   **Reading: University of California, Berkeley: Philip Stark's
    *SticiGui*: “Chapter 7: Correlation and Association”**
    Link: University of California, Berkeley: Philip Stark's *SticiGui*:
    [“Chapter 7: Correlation and
    Association”](http://www.stat.berkeley.edu/~stark/SticiGui/Text/correlation.htm)
    (HTML and Java)  
        
     Instructions: Read Chapter 7 for a discussion on the difference
    between correlation and association between two variables. When two
    variables are said to be highly correlated, it does not mean that
    one is causing the other. Pay special attention to the formula for
    computing the correlation value. There are several exercises and
    Java applets embedded in the text that are meant to further
    reinforce your learning.  *Do not skip these exercises!*  For
    instructions on how to navigate these exercises, see “Special
    Instructions on *SticiGui* Exercises and Java Applets” in the
    “Course Information” section above.  This resource covers the topics
    outlined in subunits 6.2.1 to 6.2.3.    
      
     Reading this chapter should take approximately 3 hours.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: YouTube: University of California, Berkeley: Philip
    Stark's *Statistics 21*: “Lecture 5”**
    Link: YouTube: University of California, Berkeley: Philip Stark's
    *Statistics 21*: [“Lecture
    5”](http://www.youtube.com/watch?v=SmzEZwFvKko&list=PLC08AC3E4790D974D&index=52&feature=plpp_video)
    (YouTube)  
        
     Also available in:  
     [iTunes
    U](http://itunes.apple.com/mt/itunes-u/statistics-21-002-fall-2009/id354823031)
    (Lecture 5)  
        
     Instructions: Watch “Lecture 5” from 41:00 to the end. This video
    is the companion to Chapter 7, with the author of the text working
    through the materials. This resource covers the topics outlined in
    subunits 6.2.1 to 6.2.3.    
      
     Viewing this lecture and pausing to take notes should take
    approximately 1 hour.  
        
     Terms of Use: This video is licensed under a [Creative Commons
    Attribution-Noncommercial-No Derivative
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to Philip Stark and the University of California. The
    original version can be found at
    [here](http://www.youtube.com/watch?v=k6YkcX6e8OU).

-   **Reading: Connexions: Susan Dean and Barbara Illowsky’s
    *Collaborative Statistics*: “Chapter 12: Linear Regression and
    Correlation, Section 6: The Correlation Coefficient”**
    Links: Connexions: Susan Dean and Barbara Illowsky’s *Collaborative
    Statistics:* [“Chapter 12: Linear Regression and Correlation,
    Section 6: The Correlation
    Coefficient”](http://www.saylor.org/site/wp-content/uploads/2011/06/MA121-6.2.1.pdf)
    (PDF)  
        
     Instructions: Study this resource, which shows the formula for
    computing the correlation coefficient. It may be useful to save this
    resource for future reference to this formula. Note that the formula
    uses the Greek letter sigma, ∑, as the summation symbol. For
    instance, ∑ X<sub>i</sub> = X<sub>1</sub> + X<sub>2</sub> +
    X<sub>3</sub> when *i* = 1, 2, 3. This resource covers the topics
    outlined in subunits 6.2.1 to 6.2.3.    
      
     Reading this article should take approximately 30 minutes.  
         
     Terms of Use: This work is licensed under a [Creative Commons
    Attribution 2.0 Generic
    License](http://creativecommons.org/licenses/by/2.0/). It is
    attributed to Susan Dean and Barbara Illowsky, and the original
    version can be found [here](http://cnx.org/content/m17092/1.6/).
    Please respect the copyright and terms of use. 

**6.2.1 The Correlation Coefficient** <span id="6.2.1"></span> 
*Note: The readings and lecture assigned below subunit 6.2 cover this
topic. The* correlation coefficient *is a numerical measure between -1
and +1. It measures the strength of linear association between two
variables. If it is close to -1, it means that two variables are
strongly but negatively related. If it is close to +1, it means that two
variables are strongly but positively related. Negative coefficients
mean that two variables move in opposite directions, while positive
coefficients mean that they move in the same direction. A coefficient of
0 means that there is no linear association between two variables. Make
sure you understand the difference between correlation and causation as
explained in that section of the text with the heading labeled
“Correlation and Association.”*

**6.2.2 The Effect of Nonlinear Association** <span id="6.2.2"></span> 
*Note: The readings and lecture assigned below subunit 6.2 cover this
topic. A nonlinear association is when the correlation coefficient is 0
(or very close to it from either side).*

**6.2.3 Computing the Correlation Coefficient** <span
id="6.2.3"></span> 
*Note: The readings and lecture assigned below subunit 6.2 cover this
topic. Make sure to read Chapter 12 by Dean and Illowsky to review how
to compute the correlation coefficient when you are given n data points
with each having a pair of X and Y values. Note that the formula uses
the Greek letter sigma, ∑, as the summation symbol. For instance, ∑
X<sub>i</sub> = X<sub>1</sub> + X<sub>2</sub> + X<sub>3</sub> when i =
1, 2, 3.*

**6.3 Regression** <span id="6.3"></span> 
-   **Reading: University of California, Berkeley: Philip Stark's
    *SticiGui* “Chapter 9: Regression”**
    Link: University of California, Berkeley: Philip Stark's *SticiGui*:
    [“Chapter 9:
    Regression”](http://www.stat.berkeley.edu/~stark/SticiGui/Text/regression.htm)
    (HTML and Java)  
        
     Instructions: Read Chapter 9 to learn how to analyze X and Y data,
    where the X variable is considered the independent variable and Y
    the dependent variable. Regression analysis is used to determine how
    the X values affect the Y values by assuming that there is a linear
    relationship between them. There are several exercises and Java
    applets embedded in the text that are meant to further reinforce
    your learning. *Do not skip these exercises!*  For instructions on
    how to navigate these exercises, see “Special Instructions on
    *SticiGui* Exercises and Java Applets” in the “Course Information”
    section above. This resource covers the topics outlined in subunits
    6.3.1 to 6.3.5.    
      
     Reading this chapter should take approximately 3 hours.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: YouTube: University of California, Berkeley: Philip
    Stark's *Statistics 21*: “Lecture 6”**
    Link: YouTube: University of California, Berkeley: Philip Stark's
    *Statistics 21:* [“Lecture
    2”](http://www.youtube.com/watch?v=O-Rb2yeofTY&list=PLC08AC3E4790D974D&index=51&feature=plpp_video)
    (YouTube)  
        
     Also available in:  
     [iTunes
    U](http://itunes.apple.com/mt/itunes-u/statistics-21-002-fall-2009/id354823031)
    (Lecture 6)  
        
     Instructions: Watch “Lecture 6” from 3:50 to the 57:50. This video
    is the companion to Chapter 9, with the author of the text working
    through the materials. This resource covers the topics outlined in
    subunits 6.3.1 to 6.3.5.    
      
     Viewing this lecture and pausing to take notes should take
    approximately 2 hours.  
        
     Terms of Use: This video is licensed under a [Creative Commons
    Attribution-Noncommercial-No Derivative
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to Philip Stark and the University of California. The
    original version can be found at
    [here](http://www.youtube.com/watch?v=EPrAKgawSnY).

**6.3.1 SD Line** <span id="6.3.1"></span> 
*Note: The reading and lecture assigned below subunit 6.3 cover this
topic. Make sure to look at Figure 9-1 and focus on how the Standard
Deviation (SD) line fits in an X-Y scatterplot.*

**6.3.2 Graph of Averages** <span id="6.3.2"></span> 
*Note: The reading and lecture assigned below subunit 6.3 cover this
topic. Make sure to look at Figure 9-2 and focus on how average values
of Y fit within class intervals of the X data.*

**6.3.3 Regression Line** <span id="6.3.3"></span> 
*Note: The reading and lecture assigned below subunit 6.3 cover this
topic. Make sure to look at Figure 9-4 and focus on how the regression
line is formed when the average values of Y are connected.*

**6.3.4 Estimating Using the Regression Line** <span id="6.3.4"></span> 
*Note: The reading and lecture assigned below subunit 6.3 cover this
topic. The regression line is expressed this way: Y = aX + b, where a is
the slope and b is the intercept of the line.*

**6.3.5 The Equation of the Regression Line** <span id="6.3.5"></span> 
*Note: The reading and lecture assigned below subunit 6.3 cover this
topic. Make sure you know how to compute a and b given the equations in
the text under the section labeled “The Equation of the Regression
Line.”*

-   **Reading: University of California, Berkeley: Philip Stark's
    *SticiGui*: “Chapter 11: Errors in Regression”**
    Link: University of California, Berkeley: Philip Stark's *SticiGui*:
    [“Chapter 11: Errors in
    Regression”](http://www.stat.berkeley.edu/~stark/SticiGui/Text/regressionErrors.htm)
    (HTML and Java)  
        
     Instructions: This is an optional reading. Read Chapter 11 on
    errors in regression. Read through this chapter if you would like to
    experience the entire course as it was presented at University of
    California, Berkeley. There are several exercises and Java applets
    embedded in the text that are meant to further reinforce your
    learning. *Do not skip these exercises!* For instructions on how to
    navigate these exercises, see “Special Instructions on
    *SticiGui* Exercises and Java Applets” in the “Course Information”
    section.  
      
     Reading this article should take approximately 3 hours.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: YouTube: University of California, Berkeley: Philip
    Stark's Statistics 21: “Lecture 6” and “Lecture 7”**
    Link: YouTube: University of California, Berkeley: Philip Stark's
    *Statistics 21:* [“Lecture
    6”](http://www.youtube.com/watch?v=O-Rb2yeofTY&list=PLC08AC3E4790D974D&index=51&feature=plpp_video)
    (YouTube) and [“Lecture
    7”](http://www.youtube.com/watch?v=ptj5DEA616o&list=PLC08AC3E4790D974D&index=50&feature=plpp_video)
    (YouTube)  
        
     Also available in:  
     [iTunes
    U](http://itunes.apple.com/mt/itunes-u/statistics-21-002-fall-2009/id354823031)
    (Lectures 6 and 7)  
        
     Instructions: These videos are optional. Watch “Lecture 6” from
    57:50 to the end, and watch “Lecture 7” from the beginning to 47:00.
    These video lectures complement Chapter 11 with the author of the
    text working through the materials.  
      
     Watching these lectures and pausing to take notes should take
    approximately 1 hour 30 minutes.   
      
     Terms of Use: The videos above are licensed under a [Creative
    Commons Attribution-Noncommercial-No Derivative
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/). They
    are attributed to Philip Stark and the University of California. The
    original versions can be
    found [here](http://www.youtube.com/watch?v=EPrAKgawSnY) and
    [here](http://www.youtube.com/watch?v=VsF3MsUUu3E).

**6.4 Spreadsheet Activity for Unit 6** <span id="6.4"></span> 
-   **Activity: College of Micronesia-FSM: Dana Lee Ling's Introduction
    to *Statistics Using OpenOffice.org, LibreOffice.org Calc*,
    4<sup>th</sup> edition: “04 Paired Data and Scatter Diagrams” and
    The Saylor Foundation’s “Spreadsheet Activity”**
    Links: College of Micronesia-FSM: Dana Lee Ling's *Introduction to
    Statistics Using OpenOffice.org, LibreOffice.org Calc,*
    4<sup>th</sup> edition*:* [“04 Paired Data and Scatter
    Diagrams”](http://www.saylor.org/site/wp-content/uploads/2012/10/BUS204-Ling-2.5.pdf)
    (PDF) and The Saylor Foundation’s [“Spreadsheet
    Activity”](http://www.saylor.org/site/wp-content/uploads/2011/08/BUS204-Subunit-2.5-Spreadsheet-Assignment-Open-Office-FINAL.ods)
    (Open Office) or [“Spreadsheet
    Activity”](http://www.saylor.org/site/wp-content/uploads/2013/03/BUS204-Subunit-6.5-Spreadsheet-Assignment-Excel-FINAL-1.xls)
    (Excel)  
      
     Also Available in:  
     [HTML](http://www.comfsm.fm/~dleeling/statistics/text.html#page-041)
    (04 Paired Data and Scatter Diagrams)  
        
     Instructions: Read through Chapter 4 of the text. For this
    activity, you will review how a spreadsheet can be used to plot
    data, determine the slope and intercept of regression line, and draw
    the regression line. The instructions for creating the scatter graph
    and regression line are in Section 4.25. However, for this activity,
    we are solving for the problem presented in Section 4.4. The
    supporting spreadsheet files (links above to both Excel and Open
    Office versions) include a tab titled “Starter File,” which contains
    everything you need to get started on the activity. Once you have
    worked through the activity, you can click on the “Solution File”
    tab to see how your finished spreadsheet should look.  
      
     Completing this activity should take approximately 2 hours.   
      
     Terms of Use: This work is licensed under a [Creative Commons
    Attribution 3.0
    License](http://creativecommons.org/licenses/by/3.0/). It is
    attributed to Dana Lee Ling and the original version can be found
    [here](http://www.comfsm.fm/~dleeling/statistics/text.html#page-041).

**6.5 Assessments for Unit 6** <span id="6.5"></span> 
-   **Assessment: Connexions: Susan Dean and Barbara Illowsky’s
    *Collaborative Statistics*: “Linear Regression and Correlation:
    Homework”**
    Link: Connexions: Susan Dean and Barbara Illowsky’s *Collaborative
    Statistics:* [“Linear Regression and Correlation:
    Homework”](http://www.saylor.org/site/wp-content/uploads/2012/10/BU204-Linear-Regression-and-Correlation-Upload.pdf)
    (PDF)  
      
     Also Available in:  
     [HTML](http://cnx.org/content/m17085/latest/)  
        
     Instructions: For this assessment, please work on the following
    problems: 1, 3, 5, 11, 15, 17, and 22. To see a problem solution, go
    the HTML version and click on the “Show Solution” link below the
    problem. You may also download this assessment as a DOC by clicking
    on the link to the right in the HTML version.  
      
     Completing this assessment should take approximately 3 hours.  
         
     Terms of Use: This work is licensed under a [Creative Commons
    Attribution 2.0 Generic
    License](http://creativecommons.org/licenses/by/2.0/). It is
    attributed to Susan Dean and Barbara Illowsky. The original version
    can be found [here](http://cnx.org/content/m17085/latest/). Please
    respect the copyright and terms of use. 

-   **Assessment: The Saylor Foundation’s “BUS204 Unit 6 Quiz”**
    Link: The Saylor Foundation’s [“BUS204 Unit 6
    Quiz”](http://school.saylor.org/mod/quiz/view.php?id=1384) (HTML)  
        
     Instructions: Complete this assessment to gauge your understanding
    of the topics covered in this unit. The correct answers will be
    displayed when you click the “Submit” button.  
        
     Completing the quiz, and reviewing if necessary, should take
    approximately 1 hour.


