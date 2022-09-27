# Product Catalog

## Weight in line

### Meta

Suitable for practicing:

* Requirements analysis
* Test design
* Code project

### Concept

Weight in line is a strongly opinionated queuing system for your e-commerce website.

### Requirements

* Queue can be activated for specific products
* Users in the queue are given encouraging feedback to keep them in the queue
* Users are at the front of the queue can see the product page

### User Stories

Louise, a user excited to buy a new PlayStation 5, wants to be able to queue until it is my turn to make a purchase

#### Business rules

* When a user visits a product page with an active queue, they join the back of the queue
* Every minute, the 10 users at the front of the queue are given access to the product page
* Once they reach the front of the queue, users have 15 minutes to make their purchase

##### Examples

Louise joins the queue for a PlayStation 5 with 100 people in front of them, waits ten minutes until they are at the front of the queue and then makes a successful purchase in 10 minutes.

Kika joins the queue with 1000 people in front of her, waits 10 minutes and then gives up.

Jackson joins the queue in position 11, waits 1 minute and then successfully makes a purchase of the last PlayStation 5
