# Excerpt from _A dialogue between Bayesianism and Frequentism

_The following is a dialogue which aims at introducing us the dichotomy between Bayesianism and Frequentism, 
the two majors schools of statistical inference whose disagreements stem from fundamentally different philosophical 
assumptions and mathematical solutions to the statistical problems underlying nature. It has a lot of inaccuracies, and I'd be very grateful if you were to point them out. I'm still a learner of Bayesian statistics. Here, TomStats, in honor to Thomas Bayes, is a character representing the former school of thought, while Fred, reminiscent of 'frequentism', would represent the latter. We'd witness the sudden interventions of AlexaNet (in reference to the deep neural network AlexNet) representing deep learning, and Simmball, representing the Symbolism school of thought._

_It's likely that we need to have some prior knowledge of both TomStats and Fred, particularly their understanding of probability. _

# Chapter I: Hypotheses beyond data

_An obscure stage is lightened up by a bright light. The curtains lift and we see two people conversing about statistics_


__ThomStats__: Sure, I guess we can agree that it's likely to rain, albeit I won't say it's highly. You see, I first have some __hypothesis__ of the weather of Monday, which is formulated based on prior observations of the weathers in the days beforehand. We don't need to go into the details, but you and I know, or you can know while I must know to be precise, that in the past days where it doesn't rain far exceeds the number of days where it rains. With this kind of observation-based hypothesis that it's unlikely to rain, when I read the passage, although I can update my prior belief to the point that you and I seem to converge into believing that rain is about to happen, we got there from different starting points and may differ in the exact probability of raining. Although both of us may get similar probabilities, mine's is mostly in tuned in the process of scientific inquiry and exploration. I mean, why wouldn't even you remotely _consider_ a prior ratio of rainy days to non-rainy days? 

...

__ThomStats__: Well, as I said before, it strikes me as odd that you imagine running an experiment multiple times and expect it to give similar results most of the time, because nobody actually re-samples and does the same statistics 20 times or 100 times in a row to check whether estimated coefficients are within an interval.  Anyhow, don't you think your assumption is strange? Assuming that the data you've sampled is representative of the population, that is, data is collected randomly and in a controlled manner, then shouldn't we be more concerned about whether our model can be random? 

__Fred__: Random model? As in random parameters?

__ThomStats__: Indeed, my dear friend. Our model parameters are the one subject to randomness, and we should focus more on quantifying the randomness of our model. Because I'm assuming that each coefficient is extracted from a probability distribution, then I can confidently talk about values which each coefficient can take and lie within 'credible' intervals. We call this process of quantifying randomness as __uncertainty__. And your frequentist methodology, my dear friend, certainly doesn't address the issue of __uncertainty__. 

__TomStats and Fred (in unison):__ Well, it's not our fault that Replication Crisis exists. We're blind to the methodologies adopted by humans in the reesearch data collection process and experimental design. They should change their ways and collect generalizable data. We technically can't ensure the fidelity and generalizability of data _collected_. 

__AlexaNet:__ Well, that's a limitation challenged by automation. As I evolve, I'll need less carefully collected and processed data and I'll slowly start working with unstructured data and solve problems you both could ever dream of solving. 

__TomStats:__ well, you've clearly learnt a lot from Fred on working with data. But AlexaNet, you really have to consider also learning how to __create hypothesis__ that may not necessarily stem from the data itself, but rather from your prior knowledge from observing the world. You need ideas to complement your expertise in probability. __You need thought beyond data__.  

_The stage lets down its curtains. And on what seems to be concluding remark by ThomStats will hopefully emerge new pursuits on how to make sense of this world beyond the data that's collected_

__References__


Arnold, J. B. (n.d.). A Set of Bayesian Notes. In jrnold.github.io. Retrieved April 3, 2022, from https://jrnold.github.io/bayesian_notes/

Heiner, M. (n.d.). Bayesian Statistics: Techniques and Models. Coursera - University of California, Santa Cruz. Retrieved April 2, 2022, from https://www.coursera.org/learn/mcmc-bayesian-statistics/

Sanderson, G. (2022, February 14). 3Blue1Brown - Bayes’ theorem. 3blue1brown. https://www.3blue1brown.com/lessons/bayes-theorem

Sprenger, J. (2013). Bayesianism vs. Frequentism in Statistical Inference. http://www.laeuferpaar.de/Papers/Bayes-vs-Freq-final-nodbl.pdf

VanderPlas, J. (2014a). Frequentism and Bayesianism: A Practical Introduction | Pythonic Perambulations. Jakevdp.github.io. http://jakevdp.github.io/blog/2014/03/11/frequentism-and-bayesianism-a-practical-intro/

VanderPlas, J. (2014b). Frequentism and Bayesianism: A Python-driven Primer. Arx. https://doi.org/https://doi.org/10.48550/arXiv.1411.5018
