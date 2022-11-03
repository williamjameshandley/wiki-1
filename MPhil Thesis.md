# Plan
## A Bayesian approach to RFI mitigation (in Radio Cosmology/Astronomy??) 
1. Abstract...
2. Introduction
	- In depth review of Bayesian inference
		- Define probability with brief example
		- Intro to bayes theorem
			- Consider examples from cosmology (e.g. model of the universe, model of the beam/sky/signal)
		- Parameter estimation
		- Model comparison
			- Leads to problem.. how do we evaluate evidence
			- Brings me to next section, sampling techniques..
	- In depth review of sampling techniques, leading to Nested Sampling
		- What is sampling?
		- Why it needed for Bayesian Inference?
		- Some examples, mcmc, etc
		- Why choose nested sampling?
		- Gives you evidences (MCEvidence (low dimensions),Simulated Annealing (tuning the annealing schedule, phase transitions) ,Sequential Monte Carlo (NS is a singular case of this, that is problem independent))
		- Good for self-tuning
		- 
		- Nested sampling theory
		- https://github.com/williamjameshandley/talks/tree/paris_maxent_2022 (up to slide 10 for current literature)
		- (beyond slide 10 for frontier problem, not necessary for this)
		- https://arxiv.org/abs/2205.15570
		- ADS for getting astro citations in bulk
		- https://adsabs.harvard.edu/abs_doc/aas_macros.sty 
	- RFI in radio cosmology
		- what is it?
		- why is it a problem?	
	- Potential applications
		- Global 21cm cosmology
			- Brief intro to theory
			- Why RFI is particular problem
			- Why a Bayesian approach is useful
		- Transients
			- Pulsars
				- Very brief theory
			- FRB's (if needed)
				- Very brief theory
			- Why our approach is useful
		- SETI (if needed)
			- Brief theory
			- Why our methods may be useful
3. Theory
	- Lift from paper, add slightly more detail where needed
4. Analysis/Testing
	- Toy model, lift from paper, add more detail if needed
	- Global 21cm example
		- Copy from paper
		- Add in total RFI % that can be lost
5. Future work: Pulsars
	- Pulsar example
              - Improve graph
        - FRB Example (if needed?)
	- Seti discussion, why particuarly useful
7. Conclusion
	- Sum up results (lift from paper,add detail if needed)
	- Future works
		- logit/machine learning
		- LST
		- compare with other rfi algorithms
			- hard to compare directly, as approach is unique, ie
			  not technically a binary classifier
		
			
			
