# Measure of Dispersion and Position

This folder contains Python notes, examples, and exercises related to **Measures of Dispersion** and **Measures of Position** in statistics.

These concepts help us understand:

* How spread out the data is.
* How a particular value compares with the rest of the dataset.
* The position of values within a dataset.

## Topics Covered

### Measures of Dispersion

Measures of dispersion describe the **spread or variability** of data.

#### Range

The difference between the maximum and minimum values.

```text
Range = Maximum Value − Minimum Value
```

#### Variance

Measures how far data values are spread from the mean.

#### Standard Deviation

Measures the average spread of values around the mean.

#### Interquartile Range (IQR)

Measures the spread of the middle 50% of the data.

```text
IQR = Q3 − Q1
```

---

### Measures of Position

Measures of position describe where a particular value lies within a dataset.

#### Percentiles

Divide data into 100 parts.

Examples:

* `P25` → 25th percentile
* `P50` → 50th percentile, also called the median
* `P75` → 75th percentile

#### Deciles

Divide data into 10 equal parts.

Examples:

* `D1` → 10th percentile
* `D5` → 50th percentile
* `D9` → 90th percentile

#### Z-Scores

A z-score shows how many standard deviations a value is away from the mean.

```text
Z = (X − Mean) / Standard Deviation
```

A positive z-score means the value is above the mean, while a negative z-score means it is below the mean.

## Practical Examples

The notebooks include examples of:

* Comparing range and variability.
* Calculating variance and standard deviation.
* Finding the Interquartile Range (IQR).
* Computing percentiles.
* Computing all deciles.
* Calculating z-scores.
* Verifying that standardized data has a mean close to `0` and a standard deviation close to `1`.

## Files

* `Measure_of_Dispersion_and_Position.ipynb` — Notes, explanations, and practical examples.
* `Exercises.ipynb` — Practice questions and coding exercises.

## Technologies Used

* Python
* NumPy
* Jupyter Notebook
* Statistics

## Learning Goal

The goal of this section is to understand how data is spread out and how individual values are positioned within a dataset using statistical measures.

