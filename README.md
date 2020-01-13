# insurance_risk
The aim of this project is to present a methodology for identifying the customers that may be at an enhanced
risk of filing a claim during their policy. The ability to effectively identify high risk customers is imperative for
accurate pricing of policies and profitability. Claims are an expense to insurance companies, thus, to
consistently under-price high risk customers will almost definitely lead to a net loss over time. Alternatively,
to over-price low/lower risk customers will drive potential customers away to cheaper policiesin the market.

This project starts with a variety of variable focused visualisations to provide contextual insight. Following
this, a random forest algorithm is tuned to the data with the goal of providing each customer with a
probability that they will launch a claim during their policy. The probabilities generated are evaluated against
a naïve baseline claim rate given by the percentage of claims found in the dataset, i.e every customer is
equally as risky. Finally, the results (probabilities) are presented in boxplot visualisations in order to explore
whether there are trends within each variable even after all other variables have been considered. 
