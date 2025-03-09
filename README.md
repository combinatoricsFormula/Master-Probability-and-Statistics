________________________________________
I. FOUNDATIONS OF PROBABILITY THEORY
________________________________________
	Core Theories & Axioms
		Kolmogorov’s Axioms (Foundation of modern probability theory)
		Classical Probability (Laplace’s Rule of Succession)
		Frequentist Probability vs. Bayesian Probability
		Law of Large Numbers (Weak & Strong)
		Central Limit Theorem (CLT) & Generalized CLT
		Boole’s Inequality & Bonferroni’s Inequality
		Markov’s Inequality, Chebyshev’s Inequality, Jensen’s Inequality
________________________________________
	Set Theory & Combinatorics
		Sigma-Algebra & Measure Theory (Mathematical foundation of probability)
		Permutations & Combinations (Factorial, Binomial Theorem)
		Inclusion-Exclusion Principle
		Dirichlet's Principle & Pigeonhole Principle
________________________________________
	Implementation
		Python: sympy.stats, numpy.random, scipy.stats
		R: prob, combinat
		SQL: Probability calculations using COUNT(), SUM(), CASE WHEN
________________________________________
II. RANDOM VARIABLES & PROBABILITY DISTRIBUTIONS
________________________________________
	Types of Random Variables
		Discrete Random Variables (Binomial, Poisson, Negative Binomial, Geometric)
		Continuous Random Variables (Uniform, Normal, Exponential, Gamma, Beta, Weibull)
		Multivariate Distributions (Multinomial, Dirichlet, Multivariate Normal)
		Mixture Models (Gaussian Mixture Models, Hidden Markov Models)
________________________________________
	Theorems & Laws Related to Distributions
		Moment Generating Functions (MGF), Characteristic Functions
		Skewness & Kurtosis (Pearson’s Coefficients)
		Cramer’s Theorem, Levy’s Continuity Theorem
		Law of the Iterated Logarithm
		Poisson Process & Exponential Waiting Times
________________________________________
	Implementation
		Python: scipy.stats.norm, numpy.random.exponential
		R: rnorm(), rpois()
		SQL: Simulated probability distributions with RAND(), PERCENTILE_CONT()
________________________________________
III. INFERENTIAL STATISTICS & HYPOTHESIS TESTING
________________________________________

	Fundamental Principles
		Maximum Likelihood Estimation (MLE) & Bayesian Estimation
		Likelihood Ratio Tests (LRT) & Wald Test
		Bayesian Model Selection & Bayesian Information Criterion (BIC)
________________________________________
	Types of Hypothesis Testing
		Z-Test, t-Test (One-sample, Two-sample, Paired t-Test)
		F-Test & Analysis of Variance (ANOVA, MANOVA)
		Chi-Square Test, Fisher’s Exact Test
		Kolmogorov-Smirnov Test, Shapiro-Wilk Normality Test
		Bootstrap & Permutation Tests
________________________________________
	Implementation
		Python: scipy.stats.ttest_ind(), statsmodels
		R: t.test(), anova(), chisq.test()
		SQL: CASE WHEN, PIVOT, FLOOR(), statistical simulations
________________________________________

IV. STOCHASTIC PROCESSES & MARKOV CHAINS
________________________________________
	Core Theories & Models
		Markov Chains (Discrete & Continuous-Time Markov Chains - CTMC, DTMC)
		Brownian Motion (Wiener Processes)
		Poisson Processes (Homogeneous & Non-Homogeneous)
		Martingales & Stopping Times
	Implementation
		Python: pymc3, hmmlearn
		R: markovchain
		SQL: Recursive Markov Chain queries
________________________________________
V. INFORMATION THEORY & ENTROPY
________________________________________
	Core Concepts
		Shannon Entropy & Cross-Entropy Loss
		Mutual Information & Kullback-Leibler (KL) Divergence
		Huffman Coding & Lempel-Ziv-Welch (LZW)
	Implementation
		Python: scipy.stats.entropy()
		R: infotheo
		SQL: Encoding simulations
________________________________________
VI. STATISTICAL MODELING & MACHINE LEARNING INFERENCE
________________________________________
	Regression & Bayesian Inference
		Linear & Non-Linear Regression (OLS, Ridge, Lasso, Elastic Net)
		Bayesian Regression (Bayesian Linear Models, Gaussian Processes)
________________________________________
	Multivariate Analysis
		Principal Component Analysis (PCA), Factor Analysis, ICA
		Canonical Correlation Analysis (CCA)

________________________________________

	Implementation
		Python: sklearn.linear_model, pymc3, tensorflow-probability
		R: lm(), brms
		SQL: Regression functions using REGR_SLOPE(), REGR_INTERCEPT()
________________________________________
VII. EXTREME VALUE THEORY & FINANCIAL STATISTICS
________________________________________
	Gumbel, Fréchet, and Weibull Distributions
		Risk Analysis & Value at Risk (VaR)
		Copulas in Dependence Modeling
________________________________________
VIII. ADVANCED COMPUTATIONAL STATISTICS
________________________________________

	Other Distributions
		Monte Carlo Methods (Rejection Sampling, Importance Sampling)
		Markov Chain Monte Carlo (MCMC, Gibbs Sampling, Hamiltonian Monte Carlo)
		Bootstrap Resampling & Jackknife Estimation
