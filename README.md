# Big-Mountain-Ski-Resort
#### Problem Statement:
What opportunities exist for Big Mountain Resort to effectively develop and implement a new pricing strategy that can maximize capitalization in their facilities investments to offset their recent additional
operating cost by $1.54M this season, and maintain the annual profit margin at 9.2%. Big Mountain Resort has recently installed an additional chair lift to help increase the distribution of
visitors across the mountain. This additional chair increased their operating costs by $1,540,000 this season. Every year about 350,000 people ski or snowboard at Big Mountain. This business profit margin
is 9.2% and the investors would like to keep it there. The business wants to know the recommendations on increased operating costs from the new chair this season, so that NNUl profit margin stays at 9.2%
Data
#### Data cleansing was performed primarily focusing on the following
</br>Handling the missing and NA values -Which were handled mostly using mean, ffill and fillna methods
</br>Removing duplicate rows However, no duplicate rows were identified
#### Findings
</br>Based on exploring the relationships between ticket price and other factors of resorts from all states, we listed out features with the highest correlation as below:
</br>● Vertical drops
</br>● FastQuads
</br>● Runs
</br>● Total chairs
</br>● Snow Making area
</br>● Night skiing capacity
![image](https://user-images.githubusercontent.com/87315447/160266139-5d879d4e-7799-46eb-844d-991e8ab4ab81.png)
#### Scenarios:
4 strategies were shortlisted and presented to the data science team, to maximize profits and revenue,
</br>● Permanently closing down upto 10 of the least used run
</br>● Increase the vertical drop by adding a run to a point 150 feet lower down but requiring the installation of an additional chair lift to bring skiers back up, without additional snow making
coverage
</br>● Same as number 2, but adding 2 acres of snow making cover
</br>● Increase the longest run by 0.2 mile to boast 3.5 miles length, requiring an additional snow making coverage of 4 acres
</br>To investigate the impacts of these 4 changes on the supported ticket price and the resort’s revenue, a predictive model was built on the dataset and used to predict supported ticket prices and revenues for the
current feature levels of Big Mountain, and then for feature levels reflecting each of these changes individually.
</br>The third scenario provided support for an increase in ticket price by $10.39 and projected over the season, to amount to $15,782,717 dollars, once the operating costs for an additional chair are taken into
consideration. This additional $10.39 a ticket, puts Big Mountain Resort, if rounded up, to $91.00 dollars aticket. This puts the resort closer to the suggested ticket price of $94.22. Additionally, closing one run , to
decrease any associated operating costs caused by having a chair lift, should be considered as well.
Chart: Heat map showing correlations among features
![image](https://user-images.githubusercontent.com/87315447/160266094-f12ecd3e-e104-45e0-bb2f-d75434642068.png)
#### The graph essentially conveys these facts :
</br>● Closing 1 run will have no impact on the supported ticket price
</br>● 3-5 runs can be closed with the same effect
</br>● Closing more than 6 runs leads to a significant price drop
![image](https://user-images.githubusercontent.com/87315447/160266117-edcaeea2-ee89-410b-b97c-a1e9e6ca4057.png)
#### Big Mountain Ticket Price comparison in market
![image](https://user-images.githubusercontent.com/87315447/160266332-e3e38ad6-d611-4fc9-8f5a-9d38897c3ba2.png)
![image](https://user-images.githubusercontent.com/87315447/160266374-034f9ba9-0ca0-414c-bb28-246b98b31a33.png)
#### Conclusion
The model suggests that Big Mountain is underpricing their tickets so the company can probably increase prices marginally ,on increasing the price of their adult weekend tickets by $10 to $15.
</br>Increase the vertical drop by adding a run to a point 150 feet lower down but requiring the installation of an additional chair lift to bring skiers back up, without additional snow making coverage 
</br>Big Mountain keeps the old price for weekdays, and adopts an increased price for weekends.
</br>The best scenario where we managed to gain the highest revenue increase possible was by  - 
</br>● adding one run
</br>● increasing the vertical drop by 150 ft
</br>● 2 acres of snow making cover
</br>● adding one Chair Lift

</br>This scenario has increased ticket price by 12% from $81 to $94.66, resulting in a bottom-line increase by $15,528,841 (After deducting operating costs = $1.54M).


