# Housing Price Analysis using Tableau and R

### Inroduction 
As part of self learning process I used a Housing dataset which includes information like .....
I used Tableau to create charts and dashboards to better understand the dataset and find some insights that can help make better decisions in this field. At the end I use R to create a prediction model in order to predict the price of a house, given some the attributes.

### Charts, Insights and My suggestions based on them

![image](https://user-images.githubusercontent.com/65595060/187789206-7f47cd4f-a99c-4848-ba28-3c862e5483e1.png)



The above two graphs shows the average housing prices for East, North, and West Regions based on the number of bedrooms and bathrooms . When you see the first graph, you will observe that, irrespective of the number of Bedrooms, houses in the North region have lower prices when compared to the houses in the East and West regions. Moreover, if you are looking to by a house in the range of 105k to 127k, North region will be the target area. If you are looking to by a house in the range of 119k to 140K, East region will be the best area to buy. If you are looking to buy a house in the range of 150k and 200k West region will be the best area to buy. Now when you look at the second graph, just like the Bedrooms, irrespective of number of bathrooms, prices for the houses in the North zone are cheaper when compared to the East and West regions. A Caveat here is if someone is looking to buy a in the west zone with 2 bedrooms, I would suggest to buy a 3 bedrooms house instead because the average prices of three bedrooms is less than the two bedrooms in the west zone .

![image](https://user-images.githubusercontent.com/65595060/187789607-541d3acd-727d-4070-9961-33e0c739ef1e.png)



Here is the graph for the average prices of houses made with bricks and without bricks. We can notice that the house made with bricks are on average $26000 higher than the houses made without bricks. 

![image](https://user-images.githubusercontent.com/65595060/187789939-5b91c083-3647-4374-b992-ccac26583ff3.png)

The scatter plot shows the correlation between the Area of the house measured in sq.ft. on the X-axis and the Average Price on the Y-axis. If you observe the graph, you will observe a positive relationship i.e., As the area of the house increases in terms of sq.ft, the average price also increases.

![image](https://user-images.githubusercontent.com/65595060/187790165-dc0cfef6-59f3-408a-b9c7-6680759a4098.png)

We see the correlation between the Number of Offers on the X-axis and the Average Price on the Y-axis. If you observe the graph, you will see an inverse relationship i.e., As the number of Offers increase, the average price decreases. For example, people are more willing to buy a house in the range of 90k to 120 k (Yellow and Green dots) when compared to the houses in the range of 130k to 150k (Orange and Blue Dots).

![image](https://user-images.githubusercontent.com/65595060/187790266-76f38f66-95ca-42e3-8206-0aefeddf1645.png)

Finally, I would like to present a prediction model for the average price for the houses based on my previous experience in multivariate regression. So, Based on the equation, someone who’s looking for a house made of bricks with 2000 sq.ft, 2 bedrooms, 2 bathrooms, 1 offer and in the North zone, the average prive will be around $141K.

![image](https://user-images.githubusercontent.com/65595060/187790183-dacf6439-e2ed-49a6-909d-767065035158.png)




