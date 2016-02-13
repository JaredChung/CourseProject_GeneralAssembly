# GeneralAssembly_CourseProject

##Problem
Using Kaggle dataset [Acquire Valued Shoppers Challenge](https://www.kaggle.com/c/acquire-valued-shoppers-challenge) can you predict which shoppers will become a repeat buyer after offering incentives?

##Motivation
Companies spend enourmous amounts of money on sales promotions with the intent to attract customers to become loyal to the product and become repeat buyers. However, most of the time there are <em>one-time deal hunters</em>. Producing a predictive model can provide targeted and personalized promotions which will not only reduce the promotional costs but also increase the return on investment

##Features

Inital Features
* id
* chain
* offer
* market
* repeattrips
* repeater
* offerdate
* category
* quantity
* company
* offervalue
* brand

Features Currently added
* Quantity bought from category, company,brand and chain

Additional Features not yet added
* Quantity bought from Category + company + brand + chain
* Total Dollar Value bought from category, company,brand and chain
* how many visits in marketshare of each product in the category
* share of customers who bought the product/category
* average price for product
* differences in seasonal spending per product
* general repeat-buy-probabilities for a product based on historical repeat buys
* how much competition a product faces
* how cheap a product is compared to other products
* time since customers first transaction
* whether user had returned the product before