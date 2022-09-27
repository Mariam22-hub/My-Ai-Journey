# Central Limit Theorm

The central limit theorem states that if you take sufficiently large samples from a population, the samples’ means will be normally distributed, even if the population isn’t normally distributed.

## Example: Central limit theorem
A population follows a Poisson distribution (left image). If we take 10,000 samples from the population, each with a sample size of 50, the sample means follow a normal distribution, as predicted by the central limit theorem (right image).

![image](https://cdn.scribbr.com/wp-content/uploads/2022/07/Central-limit-theorem.webp)

## What is the central limit theorem?
The central limit theorem relies on the concept of a sampling distribution, which is the probability distribution of a statistic for a large number of samples taken from a population.

Imagining an experiment may help you to understand sampling distributions:

Suppose that you draw a random sample from a population and calculate a statistic for the sample, such as the mean.
Now you draw another random sample of the same size, and again calculate the mean.
You repeat this process many times, and end up with a large number of means, one for each sample.
The distribution of the sample means is an example of a sampling distribution.

The central limit theorem says that the sampling distribution of the mean will always be normally distributed, as long as the sample size is large enough. Regardless of whether the population has a normal, Poisson, binomial, or any other distribution, the sampling distribution of the mean will be normal.

A normal distribution is a symmetrical, bell-shaped distribution, with increasingly fewer observations the further from the center of the distribution.

### Central limit theorem formula

Fortunately, you don’t need to actually repeatedly sample a population to know the shape of the sampling distribution. The parameters of the sampling distribution of the mean are determined by the parameters of the population:

The mean of the sampling distribution is the mean of the population.
  #### μM = μ
  
The standard deviation of the sampling distribution is the standard deviation of the population divided by the square root of the sample size.
  ![image](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMIAAACFCAMAAAA+YtfXAAAAMFBMVEX///8AAACnp6eysrKMjIx8fHzh4eHw8PDp6eloaGhNTU2ampq9vb3Q0NDZ2dnHx8dnm0/cAAACuElEQVR4nO2a2WLCIBBFM9mNsf7/3xYXbMiCwCBc7JwXSGsIJ8mwjFaVgAGVzFMh7x1kIQoIiAICooCAKCAgCgiIAgKigIAoICAKCIgCAqKAgCggIAoIiAICEAp9fdokqt1BUGipHatqPJer0FH9qNS64kd+hTNNunqiOaCB7AojUaPrDdHg30J2BdXtXtf7hY472RW6RfwORK1/C9kVjCEoYDwShRh8gYKKhVHXxzJjQY1IF13/KXNEUqPQa06uy5wXFvPZEPQQABRUNDwDoKUu5HwABbVK6n7U1NyFrfIgFB77hVPdv//kHhAKPEQBAVFAQBQQEAUE3ijw8mxpsCu459kOfv+aAquCR54NVIGdZ9tcjP+zZj8Ffp4tDRYFfp4tDRYFfp4tDRYFrwwPZjj/N4WM2GOBmWdLg31EWuXZPveacFq0KPDzbB7d8J7QFucahQk7z+ZMwJy8ONkoVnDzbM6w3k37SnWVZ9P3JXY08Npz2S/85dmuREqpaqfLwecDO/FJhTXNbfE6TuP7T/r0gfdQfTeeahNUTYHJz8M+pFVQO4fIbxE7srwV+sWEF4fkCl1NcUOBPbz5KtSzCukT65LrHiRWmG9zXRdzycefY7wUhuY+LYwU+JXSbgfSKiwm51izs9HUs+H+PNHkfpNyJyTNu1HfjprHAs95VZZZYfU81YqY6u5yX8nQ1bUNo0jO+pVUh+d7ZXbfJuZV2ATV63hwDzdUBY98Q1aF7cgmCunQF912sxCFV88LVVgkJvbm+IIUjpIIJSnQ/vquBIXqCxSq5ZPY+9em9rY5o0jEocJMeityW+c55kBzKlj+fviY9lozilR4dNChMaNIxncoxGvLKNIR8YK5984REAUERAEBUUBAFBAQBQREAQFRQEAUEBAFBEQBAVFAQBQQ+CKFksl7BwXNL9cECZD5jtp5AAAAAElFTkSuQmCC)

Where:

- X̄ is the sampling distribution of the sample means
- N is the normal distribution
- µ is the mean of the population
- σ is the standard deviation of the population
- n is the sample size
