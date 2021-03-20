# AI Builder final Project
Final project proposal for the AI course of the University of Helsinki


# Idea in a nutshell
Optimisation of baking goods availability and leftovers in the stores of a bakery chain with a central bakery distribution centre. The optimisation leads to a reduction of waste and less wasteful usage of resources. This in turn leads to cost reduction and increase of revenue for the owner of the bakery chain.


# Background
What is the problem your idea will solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

A bakery chain supplies its baking goods from a central bakery facility to its cafes and stores. The stores of a bakery chain experiences sometimes oversupply, sometimes lack of baking goods in the stores when needed. 

The idea is to optimise the distribution of goods to avoid a lack of goods and leftovers in the stores.

### Revenue loss
Sometimes goods could be sold at one bakery store but the particular good is not available, whereas the respective good is readily available in another store. The bakery chain experiences a loss of revenue.

### Leftovers
Some stores experiences leftovers after the store is closing for the day whereas another store could have sold those goods if they would have been available.

This kind of issue happens almost every day. 

### Cost and Speed of goods distribution
Another challenge would be speed of delivery and with this route optimisation.


# Data and AI techniques:
What data sources does your project depend on? Almost all AI solutions depend on some data. The availability and quality of the data are essential. Which AI techniques do you think will be helpful? Depending on whether you've been doing the programming exercises or not, you may choose to include a concrete demo implemented by coding, using some actual data!

### Data
* Location of stores, central bakery
* Baking Goods of relevance
* Availability of baking goods in the stores
* Goods in deliveryvehicle
* Sales of baking goods
* Map of relevant area
* Traffic condition


### Data Acquisition
Location of stores 
+ can easily be found from any map application - one time manual

Baking Goods
+ from inventory list of the bakery chain - one time manual entry,

Availability of Baking Goods
+ sensors in the display tray
+ counting based on initial stock and sales data from POS

Sales Data
+ POS

Map
+ Google Map API

### AI Technique
The overall solution consists of several components.

Optimisation of the route for daily goods distribution from central bakery to stores
Online route generation based on triggers from stores with lack of goods


# How is it used

What is the context in which your solution is used, and by whom? Who are the people affected by it? It’s important to appreciate the viewpoints of all those affected

A good solution might affect various parties, especially the owner of the bakery chain should experience some cost reduction as lesss resources would be required and wasted. On top of that more revenue would lead to a higher income. Eventually customer satisfaction might be positively affected.

### Owner of the Bakery Chain

### Store Manager/Employees

### Customer

### Delivery Service

.

# Challenges: 
What does your project not solve? It’s important to understand that any technological solution will have its limitations.
What next: How could your project grow and become something even more?


# Acknowledgments: 
If you’re using open source code or documents in your project, make sure you give credit to the creators. Mention your sources of inspiration, too.
