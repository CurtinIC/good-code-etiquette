# good-code-etiquette

This workshop was put together by Paul Hancock (Curtin University), Rebecca Lange (Curtin University), and Manodeep Sinha (Swinburne University of Technology). It was first presented at the 2019 Harley Wood School for Astronomy -> see the original fork of this repo.

This version was adapted to better cater for a more general audience and include information on R (in the presentation only at this point in time).

---

“Programs must be written for people to read, and only incidentally for machines to execute.”
― Harold Abelson, Structure and Interpretation of Computer Programs 

---

We will use peardeck for the presentation.

Go to [joinpd.com](https://app.peardeck.com/join) and type in the code given you.
You will likely need to sign in with you google account.

## Session 1: Interactive lecture, intro to coding style and practices
Examples explored:
- [Readability](Readbility.ipynb)
- [Structure](Structure.ipynb)
- [Documentation](Documentation.ipynb)
- [Exception](Excepttions.ipynb)
- [DRY examples](DRYexamples.ipynb)
- [Testing](Testing.ipynb)
- [Vectorize](Vectorize.ipynb)

## Session 2: Hands on project work, applying skills to (intentionally) crappy code

After installing `conda`, please do `conda env create -f code-environment.yml`

### Data

In this part of the workshop we will look at an example code to reproduce HR diagrams using Gaia data.
We can query the Gaia public database and download the required data.
However, the query run in the notebook takes a long time so the data is made available here:

Data can be found here:

- Full dataset of 3.6GB
[In votable format](https://www.dropbox.com/s/3hsijr0fsj6evjb/async_20190630210155.vot?dl=0)

- Full dataset as a pickled dataframe
[As a pkl file](https://www.dropbox.com/s/4jat5yjmb7okwi9/async_20190630210155.pkl?dl=0)

- sample dataset, subset of 10000 lines -> please download this for the workshop
[vot table subset](https://www.dropbox.com/s/3hczxo7vtn7zia7/async_subset.vot?dl=0)

## Session 3: Revision and Benchmarking

- When and What to Optimise
- Timing Code Snippets
- Profiling Code
- Parallelising Code
- Advanced Track

## Licence

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">CIC Good Code Etiquette workshop</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/CurtinIC/good-code-etiquette" property="cc:attributionName" rel="cc:attributionURL">Rebecca Lange</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/ADACS-Australia/good-code-etiquette" rel="dct:source">https://github.com/ADACS-Australia/good-code-etiquette</a>.
