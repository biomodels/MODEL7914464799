# MODEL7914464799: Shannon2004_VentricularMyocyte

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL7914464799.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL7914464799.git@20140916`

## Usage

Importing the model package.

`import MODEL7914464799 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**A mathematical treatment of integrated Ca dynamics within the ventricular myocyte.**   
Shannon TR, Wang F, Puglisi J, Weber C, Bers DM. _Biophys J._
[15347581](http://www.ncbi.nlm.nih.gov/pubmed/15347581) , doi:
[10.1529/biophysj.104.047449](http://dx.doi.org/10.1529/biophysj.104.047449)  
**Abstract:**   
We have developed a detailed mathematical model for Ca2+ handling and ionic
currents in the rabbit ventricular myocyte. The objective was to develop a
model that: 1), accurately reflects Ca-dependent Ca release; 2), uses
realistic parameters, particularly those that concern Ca transport from the
cytosol; 3), comes to steady state; 4), simulates basic excitation-contraction
coupling phenomena; and 5), runs on a normal desktop computer. The model
includes the following novel features: 1), the addition of a subsarcolemmal
compartment to the other two commonly formulated cytosolic compartments
(junctional and bulk) because ion channels in the membrane sense ion
concentrations that differ from bulk; 2), the use of realistic cytosolic Ca
buffering parameters; 3), a reversible sarcoplasmic reticulum (SR) Ca pump;
4), a scheme for Na-Ca exchange transport that is [Na]i dependent and
allosterically regulated by [Ca]i; and 5), a practical model of SR Ca release
including both inactivation/adaptation and SR Ca load dependence. The data
describe normal electrical activity and Ca handling characteristics of the
cardiac myocyte and the SR Ca load dependence of these processes. The model
includes a realistic balance of Ca removal mechanisms (e.g., SR Ca pump versus
Na-Ca exchange), and the phenomena of rest decay and frequency-dependent
inotropy. A particular emphasis is placed upon reproducing the nonlinear
dependence of gain and fractional SR Ca release upon SR Ca load. We conclude
that this model is more robust than many previously existing models and
reproduces many experimental results using parameters based largely on
experimental measurements in myocytes.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **shannon, wang, puglisi, weber, bers, 2004,
version04**
](http://www.cellml.org/models/shannon_wang_puglisi_weber_bers_2004_version04)  
The original CellML model was created by:  
**Fink, Martin,**   
Oxford University  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


