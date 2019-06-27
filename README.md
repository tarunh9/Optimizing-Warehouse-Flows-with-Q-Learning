# Optimizing-Warehouse-Flows-with-Q-Learning

BUSINESS CASE </br></br>
The Warehouse belongs to an online retail company that fills products to its customers and inside these warehouse the products are a stored in twelve different locations twelve different locations from A to L. Each of these letters here are one specific location where the products are stored and of course there are grouped by similar product categories. The priority is given based on some sensitive and high value products. </br>

The structure of the warehouse.</br>
![](pics/warehouse.png)
</br>

The company has the orders placed by online customers and we have an warehouse robot to collect products from these twelve different locations in the warehouse. It is connected to two systems, the first system is not an AI but is used to produce real time ranking of the warehouse areas based on the customer orders. Here we take an instance of the priority ranking as shown below. </br>

![](pics/priority.png)
</br>
The second system which is of course an AI is used to figure out the shortest route to go to locations. The robot has to go by an intermediate area before it reaches the desired location. This model looks very simple but is really powerful and useful as the complexities on the structure of the warehouse increases.</br>
