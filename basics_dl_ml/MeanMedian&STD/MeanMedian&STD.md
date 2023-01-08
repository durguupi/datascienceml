
# Mean , Median & Standard Deviation

The mean, median, and standard deviation are all statistical measures that are used to describe the central tendency and dispersion of a dataset.

The `mean` is the average of a dataset, and is calculated by adding up all of the values in the dataset and dividing by the number of values. The mean is sensitive to outliers (extreme values) in the dataset, so it may not always be the best measure of central tendency.

The `median` is the middle value of a dataset when the values are ordered from least to greatest. The median is less sensitive to outliers than the mean and is a better measure of central tendency for datasets with extreme values.

The `standard deviation` is a measure of the dispersion of a dataset, and is calculated by taking the square root of the variance. The variance is calculated by taking the average of the squared differences between the values and the mean of the dataset. The standard deviation is a useful measure of dispersion because it is in the same units as the original data.

## Symbols

```css
Mean : "μ" (mu)

Median : "M"

Standard Deviation : "σ" (sigma)
```

## Examples

```javascript
[2, 3, 3, 5, 6, 7, 8, 8, 9]

To calculate the mean of this dataset, 
we add up all of the values and divide by the number of values:

(2 + 3 + 3 + 5 + 6 + 7 + 8 + 8 + 9) / 9 = 56 / 9 = 6.22

So the mean of this dataset is 6.22.
```

```javascript
To calculate the median of this dataset, 
we first need to order the values from least to greatest:

[2, 3, 3, 5, 6, 7, 8, 8, 9]

There are 9 values in the dataset, so the median is the 5th value:

Median = 6
```

```javascript
To calculate the standard deviation of this dataset, 
we first need to calculate the variance.

To do this, we subtract the mean from each value, square the differences, 
and take the average of the squared differences:

(2 - 6.22)^2 + (3 - 6.22)^2 + (3 - 6.22)^2 + (5 - 6.22)^2 + (6 - 6.22)^2 
+ (7 - 6.22)^2 + (8 - 6.22)^2 + (8 - 6.22)^2 + (9 - 6.22)^2 / 9

= 24.68 + 0.36 + 0.36 + 2.84 + 0.04 + 0.84 + 1.64 + 1.64 + 2.44 / 9

= 14.24 / 9

= 1.58

Then, we take the square root of the variance to get the standard deviation:

Standard deviation = sqrt(1.58) = 1.25

So the standard deviation of this dataset is 1.25.
```

## Difference between variance & standard deviation

* The variance of a dataset is the average squared deviation of the values from the mean.
* It is calculated by summing the squared differences between each value and the mean, and dividing the result by the number of values in the dataset.
* The variance is often used to describe the dispersion of a dataset because it is sensitive to outliers (extreme values) in the dataset.

* `The standard deviation is the square root of the variance.`
* It is a more intuitive measure of dispersion because it is expressed in the same units as the original data.
* The standard deviation is the `average distance of the values from the mean`.

> In summary, the variance is the average squared deviation of the values from the mean,
while the standard deviation is the average distance of the values from the mean.
The standard deviation is the square root of the variance.

## Lessons Learned

The mean, median, and standard deviation can be used to describe the central tendency and dispersion of a dataset.

In this example, the mean is slightly higher than the median, which suggests that the dataset has a positive skew
(meaning that there are a few large values that are pulling the mean up).

The standard deviation is relatively small, which means that the valuesin the dataset are mostly concentrated around the mean
