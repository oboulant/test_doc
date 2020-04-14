## The Optimal COVID-19 Quarantine and Testing Policies

### General information
<span style="margin-left:2em">
**Authors** : Facundo Piguillem, Liyan Shi </br>
**Date of publication** : March 27th, 2020 </br>
**Paper** : Available [here](https://https://www.researchgate.net/profile/Facundo_Piguillem/publication/340226829_The_Optimal_COVID-19_Quarantine_and_Testing_Policies/links/5e7de548a6fdcc139c09055d/The-Optimal-COVID-19-Quarantine-and-Testing-Policies.pdf) </br>
**Code available** : no
<span>
	
### Related Public policy

<details>
	<summary> <b>Government policies model-based scenario</b> </summary>
	
* Multiplicative term in infection rate in function of variable level of working interactions in time. 
* Symptomatically infectious, and asymptomatic tested, if tests are available, are isolated and don't spread the virus
	
</details>

### Technical information

**Type of model** : Compartimental </br>
**Technical description** : SEIR, optimal control </br>
**Historical data w/ quarantine** : Early data in Italy (calibration only) </br>
**Optimization formulation** : Maximization of a welfare function with hamiltonian formulation
<details>
	<summary><b>Assumptions</b></summary>
	
1. Recovered and death rate depend on number of infectious and hospital capacity
2. Some economical hypothesis (like production=consumption)

</details>
<details>
	<summary><b>Input parameters</b></summary>
	
Essentially :

* contagion rate,
* exposed to infected rate, 
* recovery rate, 
* death rate if treated, 
* death rate if untreated, 
* hospital capacity, 
* initial exposed, 
* critical mass, 
* daily discount rate

</details>

**Output variables** : Optimal level of activity trajectory

### Comments/Issues

<details>
	<summary><b>Remarks</b></summary>

Model formulated in terms of economic loss, gives the optimal trajectory of the intensity of lockdown. Demands lot of exogenously fixed or calibrated parameters.

</details>
