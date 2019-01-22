{
  "title": "Bayesian Regression in Blavaan (Using Jags)",
  "date": "2018-11-03T12:41:05-05:00",
  "link": "https://www.rensvandeschoot.com/tutorials/bayesian-regression-blavaan/",
  "description": "This tutorial provides the reader with a basic tutorial how to perform a regression in Blavaan.",
  "tags": ["Blavaan","tutorial", "Bayesian", "Jags"],
  "fact": "",
  "featured":true
}

This tutorial provides the reader with a basic tutorial how to perform a **Bayesian regression** in [Blavaan](https://faculty.missouri.edu/~merklee/blavaan/)m using Jags instead of Stan as a MCMC sampler. You can find the Blavaan Jags tutorial [here](tutorials/blavaan-regression-stan). We will not delve into the the differences between Stan and Jags here (a technical explanation can be found [here](http://www.jmlr.org/papers/volume15/hoffman14a/hoffman14a.pdf) and a more accessible blog post [here](https://statmodeling.stat.columbia.edu/2017/11/30/not-compare-speed-stan-something-else/)). For now it suffices to say that Stan is more efficient, especially for complex models. While using Blavaan the biggest difference is how you specify the priors. Instead of using a variance, as in Jags, Stan uses standard deviations.

Throughout this tutorial, the reader will be guided through importing data files, exploring summary statistics and regression analyses. Here, we will exclusively focus on [Bayesian](https://www.rensvandeschoot.com/a-gentle-introduction-to-bayesian-analysis-applications-to-developmental-research/) statistics.

In this tutorial, we start by using the default prior settings of the software.  In a second step, we will apply user-specified priors, and if you really want to use Bayes for your own data, we recommend to follow the [WAMBS-checklist](https://www.rensvandeschoot.com/wambs-checklist/), also available in other software.

**You can find the whole tutorial [here](https://www.rensvandeschoot.com/tutorials/bayesian-regression-blavaan/")**
