# Diamonds
### (EDA and Predict the price using linear Regression)

## Dataset

> The data consists of information regarding 54,000 round-cut diamonds, including
price, carat, and other diamond qualities. The dataset can be found in the
repository for R's ggplot2 library [here](https://github.com/tidyverse/ggplot2/blob/master/data-raw/diamonds.csv),
with feature documentation available [here](http://ggplot2.tidyverse.org/reference/diamonds.html).

> For the case study, we will concentrate only the variables in the top five bullet points: price and the four 'C's of diamond grade. Our focus will be on answering the question about the degree of importance that each of these quality measures has on the pricing of a diamond.

### Columns:-

	- price: Price in dollars. Data was collected in 2008.

	- carat: Diamond weight. 1 carat is equal to 0.2 grams.

	- cut: Quality of diamond cut, affects its shine. Grades go from (low) Fair, Good, Very Good, Premium, Ideal (best).

	- color: Measure of diamond coloration. Increasing grades go from (some color) J, I, H, G, F, E, D (colorless).

	- clarity: Measure of diamond inclusions. Increasing grades go from (inclusions) I1, SI2, SI1, VS2, VS1, VVS2, VVS1, IF (internally flawless).

	- x, y, z: Diamond length, width, and depth, respectively, in mm.

	- table: Ratio of width of top face of diamond to its overall width, as a percentage.

	- depth: Proportional depth of diamond, as a percentage. This is computed as 2 * z / (x + y), or the ratio of the depth to the average of length and width.

## Packages

> Numpy, Pandas, Matplotlib, Seaborn, Sklearn

## Summary of Findings

1- the mode cut quality for diamonds in this dataset is the highest grade, Ideal. There is a consistent decrease in number of diamonds of lower cut grades.

2- There is a right-skew in the clarity grades represented in the dataset, with most of the diamonds collected having slight or very slight inclusions (SI2, SI1, VS2, VS1). There are very few diamonds with visible inclusions (I1).

3- Larger diamonds are more likely to receive lower categorical quality grades, while high quality grades are more likely to have their numbers made up of smaller diamonds. Since carat weight appears to be a major driver of price, this helps to explain the surprising marginal effect of diamond quality against price.

4- The prdiction using simple linear regression acheive accuracy 85%

5- The prdiction using Multiable linear regression acheive accuracy 91%


