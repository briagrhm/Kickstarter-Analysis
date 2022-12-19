# Kickstarting with Excel

## Outcomes Based on Launch Date/Goals

### Overview  
    To show the how both the launch date affected project outcomes compared to the money goals set for the projects. To see which projects which projects were successful, failed and canceled. This would give a better idea of which months produced the most succesful projects as well as the months that failed. Also what the ideal money goal is for a successful project and what range of goals tend to fail. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
        The most successful launch date month is May and June is a close second. Summer months seem to do better when compared to fall and winter.

### Analysis of Outcomes Based on Goals
        A budget less than $5000 seems to be the most ideal when looking Outcomes based on projected project goals. There is a 70% success rate for $1000-4999 and 76% for less than $1000. 

### Challenges and Difficulties Encountered
        Challenges that I encountered were with both pivot table and the line chart. For the pivot tabel I was having a hard time getting the months to show up but after playing around with the filters in the row labels I was able to select for the months to show. For the line graph I was having difficulties with the nesting of the formulas for the countifs. The way I overcame these were making sure that my formula was correct, by adding the necessary commas and making sure the formula was consistent throughout each cell. This is the code I used '=COUNTIFS('Kickstarter Challenge'!D:D,">1000",'Kickstarter Challenge'!F:F,"successful", 'Kickstarter Challenge'!Q:Q, "plays",'Kickstarter Challenge'!D:D,"<=4999")' It also helped to look back at previous examples to help with calculation errors that produced '#DIV/0'. '=IFERROR(ROUND(B12/E12*100,0),0)'
## Result

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    Two conclusions I can draw is that it is better to launch in the summer rather than the fall and winter because the 1st and 2nd highest on success numbers are in May and June. The second is that December is the worst month it has about the same amount of successful launches as failed launches. 
- What can you conclude about the Outcomes based on Goals?
    I am able to conclude from the outcomes based on goals that having a smaller budget is better to something below $5000. Once I am past that range my percentage of success decreases. 

- What are some limitations of this dataset?
    Limitations of this data is that although it shows the best month to launch. You dont really know why the projects are doing better in that specific time frame. Also maybe a larger pool of projects with a more diverse amount of money goals. There were a significant amount of projects with lower goals than higher. It may be skewing the results to show a higher failure rate based on the sample size. 

- What are some other possible tables and/or graphs that we could create?
    We could do a graph looking at the succesful months compared to the successful goal of projects. Since we know the best months for succesful projects and what the ideal money goal is for those projects. 
