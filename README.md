# Kaggle-Home-Depot-Product-Search-Relevance
This is a Kaggle project named Home-Depot-Product-Search-Relevance.

We are given a dataset that contains a number of products and real customer search terms from Home Depot's website. The challenge is to predict a relevance score for the provided combinations of search terms and products. To create the ground truth labels, Home Depot has crowdsourced the search/product pairs to multiple human raters. The relevance is a number between 1 (not relevant) to 3 (highly relevant).

We are provided with the following information:<br />
  >id - a unique Id field which represents a (search_term, product_uid) pair<br />
  product_uid - an id for the products<br />
  product_title - the product title<br />
  product_description - the text description of the product (may contain HTML content)<br />
  search_term - the search query<br />
  name - an attribute name<br />
  value - the attribute's value<br />
  relevance - the average of the relevance ratings for a given id

Our task is to build up a regression model, and for each id in the test set, it should predict a relevance, which is a real number in [1,3].
