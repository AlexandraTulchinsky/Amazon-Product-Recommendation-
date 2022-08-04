## Amazon Product Recommendation 

#### Objective

• Scrape product reviews and customer feedback from Amazon.

• Use different NLP moddels to determine whether a customer should purchase that product.

#### Outcomes

• RoBERTa model was used instead of VADER to draw insights. RoBERTa model was found to produce more accurate results.

• Product was assessed on a 5 scaled star rating.

• The product scored 5 stars, 75% of the time.

• The product had high positive feedback even when it earned a 3 star and 4 star rating.

• Outlier found and ignored : 5 star rating with very low positive feedback (contradiction).

#### Decision

• The product is worth the purchase based on the volume of high positive feedback
