# A blue book for Bulldozers

The goal of the contest is to predict the sale price of a particular piece of heavy equiment at auction based on it's usage, equipment type, and configuaration. The data is sourced from auction result postings and includes information on usage and equipment configurations.

In this notebook we emphasize the understanding of the model and the impact of each variable on the predicted price.
We are using a random forest as model, but we mainly focus on partial dependency plot from ([PDPbox](https://github.com/SauceCat/PDPbox)) to evaluate the influence of each variable on the prdicted price. 
