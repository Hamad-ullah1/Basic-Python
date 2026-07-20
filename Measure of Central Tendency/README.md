# Measure of Central Tendency

This folder contains Python notes, examples, and exercises related to **Measures of Central Tendency**.

Measures of central tendency are statistical methods used to find a central or typical value in a dataset.

## Topics Covered

### Mean

The **mean** is the average value of a dataset.

```text
Mean = Sum of all values / Number of values
```

Example:

```python
data = [10, 20, 30]

mean = (10 + 20 + 30) / 3
# 20
```

### Median

The **median** is the middle value after the data has been sorted.

* For an odd number of values, the middle value is the median.
* For an even number of values, the average of the two middle values is the median.

### Mode

The **mode** is the value that appears most frequently in a dataset.

A dataset can have:

* One mode: **Unimodal**
* Two modes: **Bimodal**
* More than two modes: **Multimodal**
* No mode: When no value occurs more frequently than another

## Practical Examples

The notebooks include examples using real-world-style data, such as:

* Daily website visitors
* Numerical datasets
* Calculating mean, median, and mode
* Handling empty lists
* Handling negative values
* Finding multiple modes
* Understanding common mistakes when calculating the median

## Exercises

The exercise notebook includes practice tasks such as:

* Modifying `mean()` to ignore negative values
* Raising an error when the input list is empty
* Modifying `mode()` to return all modes
* Exploring whether the mean and median can be equal while the mode is different
* Understanding why a simple median implementation can fail for an even number of values

## Files

* `Measure_of_Central_Tendency.ipynb` — Notes and explanations of mean, median, and mode.
* `Exercise_measure_of_central_Tendency.ipynb` — Practice exercises and coding problems.

## Technologies Used

* Python
* Jupyter Notebook
* Statistics

## Learning Goal

The goal of this section is to understand the basic measures of central tendency and implement them using Python.
