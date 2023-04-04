# Demand-Price-Optimization

The Newsvendor Model is a stochastic optimization problem used in inventory management to help determine the optimal order quantity for a product that has uncertain demand. The model is based on the concept of the newsvendor who must decide how many newspapers to order for the next day in order to maximize their profits. The model can be applied to a wide range of products and industries and provides a useful framework for businesses to make informed decisions about their inventory levels and order quantities. In its simplest form, the newsvendor problem consists only of the cost price of printing the newspaper and the selling price. The optimal quantity of papers to be printed will be calculated based on the previous day's demand. The optimal quantity will be determined such that the expected value of profit is maximized.

In this project, I am extending the concept and application of the newsvendor model in a few different ways to make a better approximation of reality and solve different business problems. Briefly stated, first extension will assume a shortage in newspapers, where I don’t have enough to satisfy the demand. In the second extension, I would incorporate a price-sensitive demand situation, where I assume that demand is affected by price linearly with error. The objective is still to determine the optimal price and quantity of newspapers to print that will maximize the expected profit. The optimal price and quantity will depend on the expected demand, the cost of producing each newspaper, the price that customers are willing to pay, and the degree of price sensitivity of the customers.

<img width="540" alt="image" src="https://user-images.githubusercontent.com/101216624/229675259-bf497660-d384-41be-8490-6fd7182c98df.png">

Below is the comparision of all the models built with the above assumptions and constraints.

<img width="674" alt="image" src="https://user-images.githubusercontent.com/101216624/229675370-3a33b50a-b96c-4cd7-a0b1-e5c59ec8ef7b.png">

<img width="614" alt="image" src="https://user-images.githubusercontent.com/101216624/229675409-be3f9475-09b5-47a1-b254-33932e7685d8.png">


