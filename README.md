# Phylogenetic Inference Using RevBayes

### [Workshop at NIMBioS](http://www.nimbios.org/tutorials/revbayes.html) - Knoxville, TN USA
### August 7-11, 2017

## Instructors

* Sebastian Höhna (lead organizer)
* Bastien Boussau
* Emma Goldberg
* Tracy Heath
* John Huelsenbeck
* Will Freyman

## Workshop Preparation

To prepare for the workshop, please see detailed information: [https://revbayes.github.io/RevBayes-NIMBioS-Workshop/workshop-prep](https://revbayes.github.io/RevBayes-NIMBioS-Workshop/workshop-prep)

## Workshop Schedule

### Detailed schedule timeline: [link](https://docs.google.com/spreadsheets/d/1zFW6yIMoHWa6_XHvesCLTyUDE3NuSoqb_ou80a9sA1g/edit#gid=0)

## Workshop Topics

Repository for slides: [https://github.com/revbayes/RevBayes-NIMBioS-Workshop/tree/master/slides](https://github.com/revbayes/RevBayes-NIMBioS-Workshop/tree/master/slides)

### Monday, 7 August - Höhna & Hülsenbeck

*Topics*

* Introduction/Overview
* Probability, Bayesian Statistics, MCMC
* Likelihood based phylogenetics [[slides](https://github.com/revbayes/RevBayes-NIMBioS-Workshop/blob/master/slides/Huelsenbeck_Aug7_Likelihood_Phylo.pdf)]
* Introduction to RevBayes [[slides](https://github.com/revbayes/RevBayes-NIMBioS-Workshop/blob/master/slides/Hoehna_Aug7_RevBayes_Intro.pdf)]

*Practical: Introduction to RevBayes*

* Tutorial PDF: [RB_MCMC_Intro_Tutorial.pdf](https://github.com/revbayes/revbayes_tutorial/raw/master/tutorial_TeX/RB_MCMC_Intro_Tutorial/RB_MCMC_Intro_Tutorial.pdf)

*Practical: Models of Molecular Evolution*

* Tutorial PDF: [RB_CTMC_Tutorial.pdf](https://github.com/revbayes/revbayes_tutorial/raw/master/tutorial_TeX/RB_CTMC_Tutorial/RB_CTMC_Tutorial.pdf)
* [Primates data](https://raw.githubusercontent.com/revbayes/revbayes_tutorial/master/RB_CTMC_Tutorial/data/primates_and_galeopterus_cytb.nex)
* [JC Rev script](https://raw.githubusercontent.com/revbayes/revbayes_tutorial/master/RB_CTMC_Tutorial/scripts/mcmc_JC.Rev)
* [GTR+I+G Rev script](http://rawgit.com/revbayes/revbayes_tutorial/master/RB_CTMC_Tutorial/scripts/mcmc_GTR_Gamma_Inv.Rev)

### Tuesday, 8 August - Höhna, Hülsenbeck, & Freyman

*Topics*

* Partition Models and Model Selection [[slides](https://github.com/revbayes/RevBayes-NIMBioS-Workshop/blob/master/slides/Hoehna_Aug8_Model_Selection.pdf)]
* Model Fit [[slides](https://github.com/revbayes/RevBayes-NIMBioS-Workshop/blob/master/slides/Hoehna_Aug8_Model_Fit.pdf)]
* MCMC Diagnostics & Convergence

*Practical: Model Selection*

* Tutorial PDF: [RB_BayesFactor_Tutorial.pdf](https://github.com/revbayes/revbayes_tutorial/raw/master/tutorial_TeX/RB_BayesFactor_Tutorial/RB_BayesFactor_Tutorial.pdf)
* [Data file](http://rawgit.com/revbayes/revbayes_tutorial/master/RB_BayesFactor_Tutorial/data/primates_and_galeopterus_cytb.nex)
* [Rev script](http://rawgit.com/revbayes/revbayes_tutorial/master/RB_BayesFactor_Tutorial/scripts/marginal_likelihood_JC.Rev)

*Practical: Partition Models*

* Tutorial PDF: [RB_Partition_Tutorial.pdf](https://github.com/revbayes/revbayes_tutorial/raw/master/tutorial_TeX/RB_Partition_Tutorial/RB_Partition_Tutorial.pdf)
* [Data files](https://github.com/revbayes/revbayes_tutorial/tree/master/RB_Partition_Tutorial/data)
* [Rev scripts](https://github.com/revbayes/revbayes_tutorial/tree/master/RB_Partition_Tutorial/scripts)

*Practical: Model Fit*

* Tutorial PDF: [RB_PosteriorPrediction_Tutorial.pdf](https://github.com/revbayes/revbayes_tutorial/raw/master/tutorial_TeX/RB_PosteriorPrediction_Tutorial/RB_PosteriorPrediction_Tutorial.pdf)
* [Data files](https://github.com/revbayes/revbayes_tutorial/tree/master/RB_PosteriorPrediction_Tutorial/data)
* [Rev scripts](https://github.com/revbayes/revbayes_tutorial/tree/master/RB_PosteriorPrediction_Tutorial/scripts)

*Practical: MCMC & Convergence*

* Tutorial PDF: [RB_MCMC_Tutorial.pdf](https://github.com/revbayes/revbayes_tutorial/raw/master/tutorial_TeX/RB_MCMC_Tutorial/RB_MCMC_Tutorial.pdf) 
* [Rev scripts](https://github.com/revbayes/revbayes_tutorial/tree/master/RB_MCMC_Tutorial/scripts)

### Wednesday, 9 August - Höhna & Heath

*Topics*

* Divergence-time estimation [[slides](https://github.com/revbayes/RevBayes-NIMBioS-Workshop/blob/master/slides/Heath_Aug9_Divergence_Time_Est.pdf)]
    * Clock Models
    * Node Calibration
    * Total Evidence Analysis

*Practical: Clock Models* 

* Tutorial PDF: [RB_ClockModels_Tutorial.pdf](https://github.com/revbayes/revbayes_tutorial/raw/master/tutorial_TeX/RB_ClockModels_Tutorial/RB_ClockModels_Tutorial.pdf)
* [Data file](https://github.com/revbayes/revbayes_tutorial/raw/master/RB_ClockModels_Tutorial/data/bears_irbp.nex)
* [Tree file](https://github.com/revbayes/revbayes_tutorial/raw/master/RB_ClockModels_Tutorial/data/bears_dosReis.tre)
* [Rev scripts](https://github.com/revbayes/revbayes_tutorial/tree/master/RB_ClockModels_Tutorial/scripts)

*Practical: Total Evidence Analysis under the Fossilized Birth-Death Process*

* Tutorial PDF: [RB_TotalEvidenceDating_FBD_Tutorial.pdf](https://github.com/revbayes/revbayes_tutorial/raw/master/tutorial_TeX/RB_TotalEvidenceDating_FBD_Tutorial/RB_TotalEvidenceDating_FBD_Tutorial.pdf)
* [Data files](https://github.com/revbayes/revbayes_tutorial/blob/master/RB_TotalEvidenceDating_FBD_Tutorial/data.zip) 
* [Rev scripts](https://github.com/revbayes/revbayes_tutorial/tree/master/RB_TotalEvidenceDating_FBD_Tutorial/scripts)

### Thursday, 10 August - Höhna, Goldberg, & Freyman

*Topics*

* Estimating Diversification Rates Through-Time
* Lineage-Specific Diversification Rates
* Character State-Dependent Diversification Rates
* Biogeography

*Practical: Basic diversification using constant-rate birth-death models*

* Tutorial PDF: [RB_DiversificationRate_Tutorial.pdf](https://github.com/revbayes/revbayes_tutorial/raw/master/tutorial_TeX/RB_DiversificationRate_Tutorial/RB_DiversificationRate_Tutorial.pdf)
* [Data files](https://raw.githubusercontent.com/revbayes/revbayes_tutorial/master/RB_DiversificationRate_Tutorial/data/primates_tree.nex)
* [Rev scripts](http://rawgit.com/revbayes/revbayes_tutorial/master/RB_DiversificationRate_Tutorial/scripts.zip)

*Practical: Diversification rates through time using episodic birth-death models*

* Tutorial PDF: [RB_DiversificationRate_Episodic_Tutorial.pdf](https://github.com/revbayes/revbayes_tutorial/raw/master/tutorial_TeX/RB_DiversificationRate_Episodic_Tutorial/RB_DiversificationRate_Episodic_Tutorial.pdf)
* [Data files](http://rawgit.com/revbayes/revbayes_tutorial/master/RB_DiversificationRate_Episodic_Tutorial/data/Primates_tree.nex)
* [Rev scripts](http://rawgit.com/revbayes/revbayes_tutorial/master/RB_DiversificationRate_Episodic_Tutorial/scripts.zip)

*Practical: Branch-specific diversification rate estimation*

* Tutorial PDF: [RB_DiversificationRate_BranchSpecific_Tutorial.pdf](https://github.com/revbayes/revbayes_tutorial/raw/master/tutorial_TeX/RB_DiversificationRate_BranchSpecific_Tutorial/RB_DiversificationRate_BranchSpecific_Tutorial.pdf)
* [Data files](http://rawgit.com/revbayes/revbayes_tutorial/master/RB_DiversificationRate_BranchSpecific_Tutorial/data/primates_tree.nex)
* [Rev scripts](http://rawgit.com/revbayes/revbayes_tutorial/master/RB_DiversificationRate_BranchSpecific_Tutorial/scripts.zip)

*Practical: Character State-Dependent Diversification*

* Tutorial PDF: [RB_DiversificationRate_CharacterDependent_Tutorial.pdf](https://github.com/revbayes/revbayes_tutorial/raw/master/tutorial_TeX/RB_DiversificationRate_CharacterDependent_Tutorial/RB_DiversificationRate_CharacterDependent_Tutorial.pdf)
* [Data files](http://rawgit.com/revbayes/revbayes_tutorial/master/RB_DiversificationRate_CharacterDependent_Tutorial/data.zip)
* [Rev scripts](http://rawgit.com/revbayes/revbayes_tutorial/master/RB_DiversificationRate_CharacterDependent_Tutorial/scripts.zip)
* [RevGadgets R package](https://github.com/revbayes/RevGadgets)

*Practical: Biogeography*

* Tutorial PDF: [RB_Biogeography_Tutorial.pdf](https://github.com/revbayes/revbayes_tutorial/raw/master/tutorial_TeX/RB_Biogeography_Tutorial/RB_Biogeography_Tutorial.pdf)
* [Data files](http://rawgit.com/revbayes/revbayes_tutorial/master/RB_Biogeography_Tutorial/data.zip)
* [Rev scripts](http://rawgit.com/revbayes/revbayes_tutorial/master/RB_Biogeography_Tutorial/scripts.zip)
* Also, the second part of the Biogeography Practical uses the Character state-dependent diversification materials above.

### Friday, 11 August - Höhna & Boussau

* Gene-tree/species-tree estimation
