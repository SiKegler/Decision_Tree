
Decision Tree Specialty Coffee Case Study

The Scenario
Imagine you've just finished the Springboard Data Science Career Track course, and have been hired by a rising popular specialty coffee company - RR Diner Coffee - as a data scientist. Congratulations!

RR Diner Coffee sells two types of thing:

specialty coffee beans, in bulk (by the kilogram only)
coffee equipment and merchandise (grinders, brewing equipment, mugs, books, t-shirts).
RR Diner Coffee has three stores, two in Europe and one in the USA. The flagshap store is in the USA, and everything is quality assessed there, before being shipped out. Customers further away from the USA flagship store have higher shipping charges.

You've been taken on at RR Diner Coffee because the company are turning towards using data science and machine learning to systematically make decisions about which coffee farmers they should strike deals with.

RR Diner Coffee typically buys coffee from farmers, processes it on site, brings it back to the USA, roasts it, packages it, markets it, and ships it (only in bulk, and after quality assurance) to customers internationally. These customers all own coffee shops in major cities like New York, Paris, London, Hong Kong, Tokyo, and Berlin.

Now, RR Diner Coffee has a decision about whether to strike a deal with a legendary coffee farm (known as the Hidden Farm) in rural China: there are rumours their coffee tastes of lychee and dark chocolate, while also being as sweet as apple juice.

It's a risky decision, as the deal will be expensive, and the coffee might not be bought by customers. The stakes are high: times are tough, stocks are low, farmers are reverting to old deals with the larger enterprises and the publicity of selling Hidden Farm coffee could save the RR Diner Coffee business.

Your first job, then, is to build a decision tree to predict how many units of the Hidden Farm Chinese coffee will be purchased by RR Diner Coffee's most loyal customers.

To this end, you and your team have conducted a survey of 710 of the most loyal RR Diner Coffee customers, collecting data on the customers':

age
gender
salary
whether they have bought at least one RR Diner Coffee product online
their distance from the flagship store in the USA (standardized to a number between 0 and 11)
how much they spent on RR Diner Coffee products on the week of the survey
how much they spent on RR Diner Coffee products in the month preeding the survey
the number of RR Diner coffee bean shipments each customer has ordered over the preceding year.
You also asked each customer participating in the survey whether they would buy the Hidden Farm coffee, and some (but not all) of the customers gave responses to that question.

You sit back and think: if more than 70% of the interviewed customers are likely to buy the Hidden Farm coffee, you will strike the deal with the local Hidden Farm farmers and sell the coffee. Otherwise, you won't strike the deal and the Hidden Farm coffee will remain in legends only. There's some doubt in your mind about whether 70% is a reasonable threshold, but it'll do for the moment.

To solve the problem, then, you will build a decision tree to implement a classification solution.
