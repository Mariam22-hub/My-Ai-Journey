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
  ![image](data:image/png;base64,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)

Where:

- X̄ is the sampling distribution of the sample means
- N is the normal distribution
- µ is the mean of the population
- σ is the standard deviation of the population
- n is the sample size
