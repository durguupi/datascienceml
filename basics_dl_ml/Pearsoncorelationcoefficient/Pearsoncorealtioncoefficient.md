
# Correlation & Pearson's Correlation Coefficient

## Correlation

* Correlation is a statistical measure that describes the `strength and direction of the relationship between two variables`.

* It is a value between -1 and 1, where -1 indicates a strong negative relationship (as one variable increases, the other decreases), 0 indicates no relationship,
and 1 indicates a strong positive relationship (as one variable increases, the other increases as well).*

* Correlation is commonly used in statistics and data analysis to measure the strength and direction of the relationship between two variables.
* It can be useful for identifying patterns in data, making predictions, and understanding the relationships between different variables.

* For example, if there is a strong positive correlation between the amount of time a student spends studying and their grades,
it means that as the amount of time a student spends studying increases, their grades tend to increase as well. On the other hand,
* if there is a strong negative correlation between the amount of time a student spends watching TV and their grades,
it means that as the amount of time a student spends watching TV increases, their grades tend to decrease.

## Correlation coefficient

* The correlation coefficient (also known as Pearson's correlation coefficient) is a measure of the strength and direction of the relationship between two variables.
* It is a value between -1 and 1, where -1 indicates a strong negative relationship (as one variable increases, the other decreases), 0 indicates no relationship,*
and 1 indicates a strong positive relationship (as one variable increases, the other increases as well).

* The correlation coefficient is commonly used in statistics and data analysis to measure the strength and direction of the relationship between two variables.
It is calculated using the following equation:*

```javascript
r = ∑(x - x̄)(y - ȳ) / √(∑(x - x̄)^2 ∑(y - ȳ)^2)
```

where:

x and y are the two variables

x̄ and ȳ are the means of the x and y variables,

∑ (sigma) represents the sum of the values

√ (square root) represents the square root of a value

## Correlation coefficient used in machine learning

* The correlation coefficient is often used in machine learning to understand the relationships between different variables in a dataset.
* It can be useful for identifying patterns in data, making predictions, and selecting features for building machine learning models.

```css
For example, if there is a strong positive correlation between a person's height and their weight,
it might be useful to include both variables as features in a machine learning model that predicts a person's weight.
On the other hand, if there is a strong negative correlation between a person's height and their weight, it might not be as useful to include both variables as features in the model.
```

In addition to understanding the relationships between different variables, the correlation coefficient can also be used to identify multicollinearity in a dataset.

* `Multicolline` arity occurs when two or more variables are highly correlated with each other, which can make it difficult to accurately interpret the results of a machine learning model.
* Identifying `multicollinearity` and addressing it appropriately can help improve the accuracy and interpretability of machine learning models.
