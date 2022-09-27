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
  \begin{equation*}\mu_{\bar{x}}=\mu\end{equation*}
The standard deviation of the sampling distribution is the standard deviation of the population divided by the square root of the sample size.
  \begin{equation*}\sigma_{\bar{x}} = \dfrac{\sigma}{\sqrt{n}}\end{equation*}
We can describe the sampling distribution of the mean using this notation:

  \begin{equation*}\bar{X}\sim N (\mu,\dfrac{\sigma}{\sqrt{n}})\end{equation*}
Where:

- X̄ is the sampling distribution of the sample means
- ~ means “follows the distribution”
- N is the normal distribution
- µ is the mean of the population
- σ is the standard deviation of the population
- n is the sample size
