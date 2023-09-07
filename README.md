# Introduction
The following repository consists of the assignment I did as a part of my coursework "Astrostatistics". The python scripts of all the assignments are uploaded in this repository.
I was required to do three assignments:

# Assignment 1:
**The assignment had four main objectives:**
<ul type="disc">
  <li>To write an MCMC code to estimate cosmological parameters h (also called the hubble parameter), and the matter density parameter Ωm, from the supernova dataset, assuming the Universe is flat and the errors are a gaussian.</li>
  <li>Use the burn-in process to reject unimportant data and plot a scatter data of the samples.</li>
  <li>To compare the theoretical values of distance modulus as a function of redshift with the observed one and plot a graph. </li>
  <li>To show how the acceptance probability changes as you change the size of the proposal distribution from very small (say 0.001) to very large (say 100).</li>
</ul>

# Assignment 2:
The assignmet uses MCMC code to analyse photographic plates from Eddington’s 1919 eclipse expedition, to determine whether the data favour Newtonian gravity or Einstein’s General Theory of Relativity.

# Assignment 3:
This assignment was an extention of the first assignmet. It had three additional tasks to be done:

<ul type="disc">

  <li> Importance sampling: Consider a non-flat prior, so the target distribution is the posterior, not the likelihood. We can still sample from the likelihood (as you have been doing), and construct
the posterior by weighting the points with the prior to get the target. This is an example of importance sampling, where we sample from a different distribution from the one we eventually
want. Apply a prior on the Hubble constant to your chain, assuming a gaussian prior with mean 0.738 and standard deviation 0.024. Now plotting all the points in the chain will give a graph
which looks the same as your previous graphs, so what should you do? Compute the mean h, Ωm with and without the prior. </li>
<li>Write and apply a Gelman-Rubin convergence test, and deduce roughly how long the chains should be for convergence. </li>



 



