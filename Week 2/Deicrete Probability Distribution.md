## Discrete Probability Distribution
Discrete probability distribution is a type of probability distribution that shows all possible values of a discrete random variable along with the associated probabilities. In other words, a discrete probability distribution gives the likelihood of occurrence of each possible value of a discrete random variable.

Geometric distributions, binomial distributions, and Bernoulli distributions are some commonly used discrete probability distributions. This article sheds light on the definition of a discrete probability distribution, its formulas, types, and various associated examples.


### What is Discrete Probability Distribution?
A discrete probability distribution and a continuous probability distribution are two types of probability distributions that define discrete and continuous random variables respectively. A probability distribution can be defined as a function that describes all possible values of a random variable as well as the associated probabilities.

### Discrete Probability Distribution Definition
A discrete probability distribution can be defined as a probability distribution giving the probability that a discrete random variable will have a specified value. Such a distribution will represent data that has a finite countable number of outcomes. There are two conditions that a discrete probability distribution must satisfy. These are given as follows:

**- 0 ≤ P(X = x) ≤ 1**. This implies that the probability of a discrete random variable, X, taking on an exact value, x, lies between 0 and 1.
**- ∑P(X = x) =1**. The sum of all probabilities must be equal to 1.

Discrete Probability Distribution Example
Suppose a fair dice is rolled and the discrete probability distribution has to be created. The possible outcomes are {1, 2, 3, 4, 5, 6}. Thus, the total number of outcomes will be 6. All numbers have a fair chance of turning up. This means that the probability of getting any one number is 1 / 6. Using this data the discrete probability distribution table for a dice roll can be given as follows:

x: 	1,	2,	3,	4,	5,	6
P(X = x)	1 / 6,	1 / 6,	1 / 6,	1 / 6,	1 / 6,	1 / 6


### Discrete Probability Distribution Formula
A discrete random variable is used to model a discrete probability distribution. There are two main functions associated with such a random variable. These are the probability mass function (pmf) and the probability distribution function or cumulative distribution function (CDF).

### Discrete Probability Distribution PMF
The probability mass function can be defined as a function that gives the probability of a discrete random variable, X, being exactly equal to some value, x. This function is required when creating a discrete probability distribution. The formula is given as follows:

**f(x) = P(X = x)**

### Discrete Probability Distribution CDF
The cumulative distribution function gives the probability that a discrete random variable will be lesser than or equal to a particular value. The value of the CDF can be calculated by using the discrete probability distribution. Its formula is given as follows:

**F(x) = P(X ≤ x)**

### Discrete Probability Distribution Mean
The mean of a discrete probability distribution gives the weighted average of all possible values of the discrete random variable. It is also known as the expected value. The formula for the mean of a discrete random variable is given as follows:

**E[X] = ∑x P(X = x)**

### Discrete Probability Distribution Variance
The discrete probability distribution variance gives the dispersion of the distribution about the mean. It can be defined as the average of the squared differences of the distribution from the mean, μ
. The formula is given below:

**Var[X] = ∑(x - μ)2 P(X = x)**


### Discrete Probability Distribution Types
A discrete probability distribution is used in a Monte Carlo simulation to find the probabilities of different outcomes. The most commonly used types of discrete probability distributions are given below.

#### 1) Bernoulli Distribution

A Bernoulli distribution is a type of a discrete probability distribution where the random variable can either be equal to 0 (failure) or be equal to 1 (success). The probability of getting a success is p and that of a failure is 1 - p. It is denoted as X ∼ Bernoulli (p). The pmf is expressed as follows:

P(X = x) = {p,if x = 11 - p, if x = 0}

#### 2) Binomial Distribution

A binomial distribution is a discrete probability distribution that gives the success probability in n Bernoulli trials. The probability of getting a success is given by p. It is represented as X ∼ Binomial(n, p). The pmf is given as follows:
P(X = x) = (nx) p^x (1−p)^n−x


#### 3) Geometric Distribution

A geometric distribution is another type of discrete probability distribution that represents the probability of getting a number of successive failures till the first success is obtained. It is given by X ∼ G(p). The formula for the pmf is given as follows:

P(X = x) = (1 - p)^x p, where p is the success probability of the trial.

#### 4) Poisson Distribution

Poisson distribution is a discrete probability distribution that is widely used in the field of finance. It gives the probability that a given number of events will take place within a fixed time period.


### How To Find Discrete Probability Distribution?

A discrete probability distribution can be represented either in the form of a table or with the help of a graph. To find a discrete probability distribution the probability mass function is required. In other words, to construct a discrete probability distribution, all the values of the discrete random variable and the probabilities associated with them are required. Suppose a fair coin is tossed twice. Say, the discrete probability distribution has to be determined for the number of heads that are observed. The steps are as follows:

- Step 1: Determine the sample space of the experiment. When a fair coin is tossed twice the sample space is {HH, HT, TH, TT}. Here, H denotes a head and T represents a tail. Thus, the total number of outcomes is 4.
- Step 2: Define a discrete random variable, X. For the example let X be the number of heads observed.
- Step 3: Identify the possible values that the variable can assume. There are 3 possible values of X. These are 0 (no head is observed), 1 (exactly one head is observed), and 2 (the coin lands on heads twice).
- Step 4: Calculate the probability associated with each outcome. In the given example, the probability can be calculated by the formula, number of favorable outcomes / total number of possible outcomes.
- Step 5: To get the discrete probability distribution represent the probabilities and the corresponding outcomes in tabular form or in graphical form.

<img src = "https://d138zd1ktt9iqe.cloudfront.net/media/seo_landing_files/discrete-probability-distribution-example-1639994583.png" width = 50%, height = 50%>

<br/>

### Important Notes on Discrete Probability Distribution

- A discrete probability distribution is used to model the outcomes of a discrete random variable as well as the associated probabilities.
- A discrete distribution is used to calculate the probability that a random variable will be exactly equal to some value.
0 ≤ P(X = x) ≤ 1 and ∑P(X = x) =1 are two conditions that must be satisfied by a discrete probability distribution.
- The examples of a discrete probability distribution are Bernoulli Distribution, binomial distribution, Poisson distribution, and geometric distribution.
