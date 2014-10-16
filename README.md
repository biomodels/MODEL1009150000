# MODEL1009150000: 

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1009150000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1009150000.git@20140916`

## Usage

Importing the model package.

`import MODEL1009150000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is the genome-scale metabolic network of a hepatocyte described in the
article:  
**HepatoNet1: a comprehensive metabolic reconstruction of the human hepatocyte for the analysis of liver physiology.**   
Gille C, Bölling C, Hoppe A, Bulik S, Hoffmann S, Hübner K, Karlstädt A,
Ganeshan R, König M, Rother K, Weidlich M, Behre J and Holzhütter HG. _Mol
Syst Biol._ 2010 Sep 7;6:411.; PmID:
[20823849](http://www.ncbi.nlm.nih.gov/pubmed/20823849) , DOI:
[10.1038/msb.2010.62](dx.doi.org/10.1038/msb.2010.62)  
Abstract:  
We present HepatoNet1, the first reconstruction of a comprehensive metabolic
network of the human hepatocyte that is shown to accomplish a large canon of
known metabolic liver functions. The network comprises 777 metabolites in six
intracellular and two extracellular compartments and 2539 reactions, including
1466 transport reactions. It is based on the manual evaluation of >1500
original scientific research publications to warrant a high-quality evidence-
based model. The final network is the result of an iterative process of data
compilation and rigorous computational testing of network functionality by
means of constraint-based modeling techniques. Taking the hepatic
detoxification of ammonia as an example, we show how the availability of
nutrients and oxygen may modulate the interplay of various metabolic pathways
to allow an efficient response of the liver to perturbations of the
homeostasis of blood compounds.

This model was taken from the supplementary materials of the article. Only the
notes and the compartment names were slightly altered.

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


