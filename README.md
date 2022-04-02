# AB-Testing-Frequentist-vs-Bayesian

A/B Testing is an extremely common practice in web optimization, clinical trials, and a range of other applications. While the Frequentist Approach is the most commonly employed method in A/B testing, a Bayesian Approach offers many advantages including: requiring fewer observations, a more straightforward analysis, and more intuitive results. Additionally, a Bayesian approach allows multi-armed bandit strategies to be employed during the experiment to reduce opportunity cost.

[AB Testing Frequentist vs. Bayesian](https://github.com/johnleraas/AB-Testing-Frequentist-vs-Bayesian/blob/main/ABTesting_Freq_v_Bayes.ipynb)
This notebook directly compares the two methodologies using conjugate priors to compute the posterior distribution in the Bayesian analysis.

[Bayesian A/B Testing Using MCMC Sampling](https://github.com/johnleraas/AB-Testing-Frequentist-vs-Bayesian/blob/main/Bayesian_ABTesting_MCMCSampling.ipynb)
This notebook focuses on the Bayesian approach and utilizes MCMC Sampling (Markov Chain Monte Carlo Sampling) to calculate the posteriod distributions. This methodology can be applied more generally, specifically in cases in which conjugate priors may not be available.
