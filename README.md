# VBA Challenge

###Overview of Project
##Purpose & Background
The purpose of this analysis was to refactor the original code to collect information about different stock options for the years 2017 & 2018 and determine whether or not each were worthy of investments. Through VBA, a macro was created to allow for easily-accessible and quicker information in order improve the original code.

###Results
##Analysis
The data below presents a comparison between the completed analysis of all stocks for years 2017 & 2018. The ticker represents the name of each abbreviated stock option as both charts contain the same companies. Total daily volume are the daily number of trades over the course of an single year. In the return column, we will find out which stocks had either a positive(green) or negative (red) growth.

![ALLSTOCKS2017](https://user-images.githubusercontent.com/102638461/163917504-21c2313f-570f-43ef-8726-43c5a391d690.png)
![ALLSTOCKS2018](https://user-images.githubusercontent.com/102638461/163917510-216da067-1e25-4975-b7bd-984b58af70f4.png)

Here, we can see that in 2017, TERP had a negative return while every other stock thrived, with some as high as nearly 200%.


In 2018, ENPH and RUN were the only two with a positive net growth, whereas every other option struggled.


##Execution Times
Through refactoring, it took 0.9375 seconds to run the code for the year 2017, whereas it took 0.8906 seconds. This allowed for a one second decrease in time in comparison towards the original code. Although I noticed that each time the code ran, it would result in a different execution time, but all were still relatively quicker than the original script.

![VBA_Challenge_2017](https://user-images.githubusercontent.com/102638461/163917542-4e08cb6e-ff6a-487f-a81f-08fb0f6906a5.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/102638461/163917555-bb36ecff-5aa4-48f1-bfb3-a7b7ee1a62ce.png)


###Summary
##Advantages & Disadvantages
The biggest advantage when it comes to refactoring the original script was that it organized the code so that programs quicker and provided clear & concise data. A disadvantage would be that its very easy to create errors in the original code, which may lead to hours of debugging and reformatting so that everything runs smoothly.

Through refactoring, the VBA script ran quicker and provided instant results, and that the code itself was easier to read. Although the most common error that I encountered was the "next without for" compile error, this was resolved by completely rewriting my code from start to finish.


