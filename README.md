# Optimization-model
COMPANY:CODTECH IT SOLUTIONS 
NAME:ATHIRA.K
INTERN ID:CT08QSM
DOMAIN:DATA SCIENCE
DURATION:4 WEEKS
MENTOR:NEELA SANTHOSH\
Optimization plays a crucial role in business decision-making by helping maximize profits while managing resource constraints effectively. In this project, we use Linear Programming (LP) to optimize the production of cakes in a bakery. The goal is to determine the optimal number of Chocolate Cakes and Vanilla Cakes to produce, ensuring efficient use of ingredients while maximizing profit.
A bakery produces two types of cakes:
Chocolate Cake
Vanilla Cake
Ingredient usage per cake was plotted using bar charts.
Profitability comparison was analyzed to see which cake contributes more profit.
The bakery has limited resources, including flour, sugar, and eggs. The challenge is to determine the optimal production quantities of each cake type to maximize profit while staying within ingredient limits.
We used the PuLP library in Python to implement the LP model. The key components of our model:
Decision Variables:
Chocolate_Cakes = Number of chocolate cakes to produce
Vanilla_Cakes = Number of vanilla cakes to produce
Objective Function:
Maximize the total profit:Profit = 5 × Chocolate_Cakes + 7 × Vanilla_Cakes
The optimization model provided the following results:
Chocolate Cakes to produce: 10
Vanilla Cakes to produce: 10
Maximum Profit: $120
This means that to achieve maximum profit while staying within ingredient limits, the bakery should produce 10 Chocolate Cakes and 10 Vanilla Cakes.
This project demonstrated how Linear Programming can be applied to a real-world business problem. By using Python and PuLP, we successfully optimized the bakery's production strategy, leading to higher profitability and efficient resource utilization. Similar approaches can be used in supply chain management, inventory optimization, and workforce planning.
Include additional constraints such as baking time and labor availability.
Expand the model for more products like cupcakes, muffins, and pastries.
Develop a user-friendly dashboard for bakery owners to input ingredient stock and receive optimal production plans automatically.




