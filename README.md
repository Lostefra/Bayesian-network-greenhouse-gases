# A Bayesian Network to model the influence of energy consumption on greenhouse gases in Italy

#### by [Lorenzo Mario Amorosa](https://github.com/Lostefra)

Here it is the [python notebook](https://github.com/Lostefra/Bayesian-network-greenhouse-gases/blob/master/main.ipynb).

This project was developed as a part of the course *Fundamentals of Artificial Intelligence and Knowledge Representation (Mod. 3) - Alma Mater Studiorum Università di Bologna*.

### Abstract

Nowadays it is well established that **global warming** is hugely caused by greenhouse gases, which are indeed responsible for trapping heat in the atmosphere. The 3 most common gases are carbon dioxide (**CO**<sub><b>2</b></sub>), methane (**CH**<sub><b>4</b></sub>) and nitrous oxide (**N**<sub><b>2</b></sub>**O**) [[1]](#first).

There are several sources of greenhouse gases, such as transportation, industry, commercial and residental. In this document I will tackle the problem in a general way, considering the impact of energy consumption on greenhouse gases emissions. Energy is indeed strictly related to almost all source factors. In particular, I will face the modelling of **causal relations** between **energy consumption and greenhouse gases in Italy** using a **Bayesian network**. The aim is to learn a model that can provide **probabilistic results given** some input **evidence**. The causal relations and their relative probabilities will be estimated by analyzing **annual growth factors** of several indicators from open source datasets of the World Bank Group (WBG) [[3]](#third). The choice of analyzing the annual growth aims to capture how the variation of an indicator can affect the others.

This work starts from a paper by Cinar and Kayakutlu (2010) [[2]](#second) in which the authors produced estimates about energy investments in Turkey given historical data. Their work helped me to come up with interesting measures to be investigated and to be represented in the Bayesian network. I could extend their work adding: a more comprehensive analysis of network properties (**conditional independencies, active trails, Markov blankets**), concise and effective high level functions (such as `query_report`, `check_assertion` and `active_trails_of`) to express the most significant properties in a readable format and the whole code **to learn the Bayesian network** from the available datasets.

### References
<a name="first">[1]</a> [*U.S. Environmental Protection Agency - Greenhouse Gas Emissions*](https://www.epa.gov/ghgemissions/overview-greenhouse-gases)

<a name="second">[2]</a> [*Didem Cinar, Gulgun Kayakutlu - Scenario analysis using Bayesian networks: A case study in energy sector*](https://www.sciencedirect.com/science/article/pii/S0950705110000110)

<a name="third">[3]</a> [*World Bank Open Data*](https://data.worldbank.org/indicator)
