# Machine Learning for Physics and Astronomy
**[Davide Gerosa](https://davidegerosa.com/)** (module lead) - davide.gerosa@unimib.it  
**UPDATE** (teaching assistant) - update@campus.unimib.it 

University of Milano-Bicocca, 2026. [BSc in Artificial Intelligence](https://www.unimib.it/undergraduate/artificial-intelligence).

## Aims

Machine learning and data mining are quickly becoming essential techniques in the field of (astro)physics. Such powerful tools provide precious insights into the laws governing natural processes and shed light on the information contained in experimental datasets. This lab provides a quick introduction to such topics, equipping students with some essential background to apply their data-science knowledge to core physical problems.

## Lectures

1. **[Probability](lectures/L01_probability.ipynb)** Probability theory. Bayes theorem. Descriptive statistics (*E: Monty Hall*)
2. **[Sampling](lectures/L02_sampling.ipynb)** Bayesian vs frequentist statistics. From the pdf to the samples: inverse transform, acceptance/rejection (*E: Black holes*)
3. **[Density estimation](lectures/L03_densityestimation.ipynb)** From the samples to the pdf: histograms, Kernel Density Estimation. (*E: Exoplanets*)
4. **[Markov chains](lectures/L04_Markovchains.ipynb)** Bayesian stats examples. Monte Carlo integrations. Markov chains. (*E: Weather forecast, N-dimensional balls*)
5. **[MCMC](lectures/L05_MCMC.ipynb)** Metropolis Hastings. MCMC diagnostics. Modern samplers. (*E: Time transients*)
6. **[Model selection](lectures/L06_modelselection.ipynb)** Bayesian model selection. Savage-Dickey density ratio. (*E: Higgs Boson*)
7. **[Nested sampling](lectures/L07_nestedsampling.ipynb)** Computing the evidence. Nested sampling. Modern samples. (*E: Time transients & Higgs Boson*)
8. **[Project](lectures/L08_project.ipynb)** (*E: The expansion of the Universe*)

## Resources

Here are some useful textbooks. The first one is easier, the second one is amazing, the third is short and sweet, the fourth and fifth ones are for the true Bayesians...

 - ["Machine Learning for Physics and Astronomy"](https://press.princeton.edu/books/paperback/9780691206417/machine-learning-for-physics-and-astronomy), Acquaviva, Princeton University Press, 2023.
- ["Statistics, Data Mining, and Machine Learning in Astronomy"](https://press.princeton.edu/books/hardcover/9780691198309/statistics-data-mining-and-machine-learning-in-astronomy), Željko, Andrew, Jacob, and Gray. Princeton University Press, 2012.
- ["Statistical Data Analysis"](https://global.oup.com/academic/product/statistical-data-analysis-9780198501558?cc=fr&lang=en&), Cowan. Oxford Science Publications, 1997.
- ["Data Analysis: A Bayesian Tutorial"](https://global.oup.com/academic/product/data-analysis-9780198568322?cc=fr&lang=en&), Sivia and Skilling. Oxford Science Publications, 2006.
- ["Bayesian Data Analysis",](http://www.stat.columbia.edu/~gelman/book/) Gelman, Carlin, Stern, Dunson, Vehtari, and Rubin. Chapman & Hall, 2013. Free!

We will make heavy use of the python programming language. If you need to refresh your python skills, here are some catch-up resources and online tutorials. 

- ["Python for Scientific Computing"](https://sbu-python-class.github.io/python-science/Introduction.html), M. Zingale
- ["Lectures on scientific computing with Python"](https://github.com/jrjohansson/scientific-python-lectures), R. Johansson et al.  
- [Python Programming for Scientists"](https://astrofrog.github.io/py4sci/), T. Robitaille et al.
- ["Learning Scientific Programming with Python"](https://www.cambridge.org/core/books/learning-scientific-programming-with-python/3D264483BC7B380A3059B3861C661237), Hill, Cambridge University Press, 2020. Supporting code: [scipython.com](https://scipython.com/).
- ["Python for non pythonians"](https://www.amazon.com/Python-non-Pythonians-Over-Programming-Languages/dp/888548686X), Rubera, Grossetti, 2019.

## Class schedule

Classes will take place on the Bicocca campus, on Wednesdays from 8.30am to 12.30pm, for a total of 36 hours. 

Our schedule is as follows. [Here is a public calendar](https://calendar.google.com/calendar/embed?src=5d8d31ed2056780a879a376955b230fe78245fd8990bff77a728da5de8e0ff0f%40group.calendar.google.com&ctz=Europe%2FRome) with the dates below, which you can import into your calendar software.


<!-- CALENDAR:START -->
1. **2026, Mar 11, 08:30am - 12:30pm**
2. **2026, Mar 18, 08:30am - 12:30pm**
3. **2026, Mar 25, 08:30am - 12:30pm**
4. **2026, Apr 01, 08:30am - 12:30pm**
5. **2026, Apr 08, 08:30am - 12:30pm**
6. **2026, Apr 15, 08:30am - 12:30pm**
7. **2026, Apr 29, 08:30am - 12:30pm**
8. **2026, May 06, 08:30am - 12:30pm**
9. **2026, May 13, 08:30am - 12:30pm**
10. **2026, May 20, 08:30am - 12:30pm**
<!-- CALENDAR:END -->

## Setup

**Coding**. Each class will be about 1h of lecture and about 3h of coding. You will need to run python, see [here for instructions](pythonsetup.md).

**News+emails**: [elearning.unipv.it/course/section.php?id=102930](https://elearning.unipv.it/course/section.php?id=102930)

**Recordings**: [elearning.unimib.it/course/view.php?id=60763](https://elearning.unimib.it/course/view.php?id=60763)



## Exams

Each lecture has an exercise at the end (actually, most of the time in class is dedicated to completing these problems!). At the end of the class, you will have to submit your codes showcasing what you've done on these problems. There will not be oral exams. The outcome will be provided as a passed / not passed statement (no numbers).

To submit your codes, register on github.com, create a new **private** repository called `machinelearning4physics_bicocca_2026_solutions`, upload your files, share it with the two of us (usernames `dgerosa` and `UPDATE`), and send us an email when you are done. See [here for detailed instructions](examsubmission.md).

You do not need to submit assignments after every lecture. Please share them all together at the end of the course, when you are ready. Exams will be cleared according to the nominal exam dates available on the student service website. 


## Past editions

- Current: [dgerosa.github.io/machinelearning4physics](https://dgerosa.github.io/machinelearning4physics)
- 2025: [github.com/dgerosa/machinelearning4physics_bicocca_2025](https://github.com/dgerosa/machinelearning4physics_bicocca_2025)
- 2024: [github.com/dgerosa/machinelearning4physics_bicocca_2024](https://github.com/dgerosa/machinelearning4physics_bicocca_2024)

## Careful...

<p align="center">
  <img src="https://imgs.xkcd.com/comics/here_to_help_2x.png" width="800" />
</p>

Credit: [xkcd 1831](https://xkcd.com/1831/).
