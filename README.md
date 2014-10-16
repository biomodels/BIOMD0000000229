# BIOMD0000000229: Ma2002_cAMP_oscillations

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000229.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000229.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000229 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
** Quantifying robustness of biochemical network models. **   
Ma L, Iglesias PA. _BMC Bioinformatics._2002 Dec 13;3:38.
[12482327](http://www.ncbi.nlm.nih.gov/pubmed/12482327),  
**Abstract:**   
BACKGROUND: Robustness of mathematical models of biochemical networks is
important for validation purposes and can be used as a means of selecting
between different competing models. Tools for quantifying parametric
robustness are needed. RESULTS: Two techniques for describing quantitatively
the robustness of an oscillatory model were presented and contrasted. Single-
parameter bifurcation analysis was used to evaluate the stability robustness
of the limit cycle oscillation as well as the frequency and amplitude of
oscillations. A tool from control engineering--the structural singular value
(SSV)--was used to quantify robust stability of the limit cycle. Using SSV
analysis, we find very poor robustness when the model's parameters are allowed
to vary. CONCLUSION: The results show the usefulness of incorporating SSV
analysis to single parameter sensitivity analysis to quantify robustness.

  

This model is originally proposed by Laub and Loomis (1998).[Laub MT, Loomis
WF (1998). A molecular network that produces spontaneous oscillations in
excitable cells of Dictyostelium. Mol Biol Cell. 9(12):3521-32. PubMED:
[12482327](http://www.ncbi.nlm.nih.gov/pubmed/12482327).  
The parameters used in this model (Ma and Iglesias, 2002), are different from
that used in the original model (Laub and Loomis, 1998), because of the
typographical errors in the original paper. The parameters used in the model
presented by Ma and Iglesias, are obtained directly from the authors of
original publication (Laub and Loomis, 1998). These parameters are also used
in the website for the Laub-Loomis model, <http://www-
biology.ucsd.edu/labs/loomis/network/laubloomis.html>.  
By using this model, Kim et al., 2006 [Kim J, Bates DG, Postlethwaite I, Ma L,
Iglesias PA. (2006) Robustness analysis of biochemical network models. Syst
Biol (Stevenage). 153(3):96-104. PubMED:
[16984084](http://www.ncbi.nlm.nih.gov/pubmed/16984084)], validate and extend
the analysis approach proposed by Ma and Iglesias (2002), by showing how
hybrid optimisation can be used to compute worst-case parameter combinations
in the model.

  

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2010 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


