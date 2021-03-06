# Bryan-Mannix-Python movie cororolation project 

In this project, we will be working in Python to find correlations between variables. To do this, I downloaded a movie data set from Kaggle that deals with many different variables. I thought it would be interesting to use tools within Python to see what factor is the most influential in ensuring a movie makes a high gross profit.

The following are the different factors that the data set comprises: Budget, company, country, director, genre, gross, name, rating, release date,  runtime,  score star, votes, writer, year.  My task is to find which one of these has the highest correlation with gross profit. 

![Screenshot (111)](https://user-images.githubusercontent.com/84920516/124481886-abb1e380-dda0-11eb-8bab-10eeabfa58b4.png)

I then went about cleaning the data. I first looked to see if there was data missing and found that there wasn't. I then changed the data type for budget and gross to make it look better while also sorting the columns. I also dropped any duplicates.  Now the data was ready to plot on a graph.

![Screenshot (112)](https://user-images.githubusercontent.com/84920516/124483502-51b21d80-dda2-11eb-989c-43661f9e009b.png)

I have a prediction that a high budget correlates with high gross profit. To see if this was the case, I used seaborn sns. regplot scatter plot to see if there was a clear correlation. At first glance at the graph, it is clear that budget and gross profit are correlated. 

![Screenshot (115)](https://user-images.githubusercontent.com/84920516/124487908-254cd000-dda7-11eb-9b0f-68e68639c1b4.png)

To see the exact correlation between gross profit and budget, i used the Pearson correlation coefficient. The most common method for numerical variables is assigning a value between − 1 and 1, where 0 is no correlation, 1 is a total positive correlation, and − 1 is an absolute negative correlation.  As you can see, there is a high correlation between gross revenue and the magnitude of the budget at 0.712. I included other variables, including score, run time, year, and votes, to see a higher correlation than budget. 

![Screenshot (117)](https://user-images.githubusercontent.com/84920516/124490915-90e46c80-ddaa-11eb-9e99-d7dc306372e1.png)

I used a heat map to make the correlations easier to see, black for low correlation, brighter colors for high correlation. As we can see, the budget does have the highest correlation, which means my prediction is correct so far. Votes also had a very high correlation to high gross profit.  However, these are only for the numeric features. Other string features still have to be measured for correlation which I will do so by changing them to numeric features. 

![Screenshot (118)](https://user-images.githubusercontent.com/84920516/124492037-d5bcd300-ddab-11eb-95d7-4c03ec6c3046.png)

Before and after pic of the tables, I changed string variables to numeric variables to analyze their correlation. 

![Screenshot (121)](https://user-images.githubusercontent.com/84920516/124493102-2680fb80-ddad-11eb-8704-48e9f6b363ec.png)
![Screenshot (122)](https://user-images.githubusercontent.com/84920516/124493126-2f71cd00-ddad-11eb-81b6-68dd7f316366.png)

As you can see with the graph involving all factors. Budget and votes still have the highest correlation with high gross profit. 

![Screenshot (123)](https://user-images.githubusercontent.com/84920516/124493437-8c6d8300-ddad-11eb-9ff1-402b66c370bb.png)












 
















