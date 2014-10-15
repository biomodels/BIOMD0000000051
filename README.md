# BIOMD0000000051: Chassagnole2002_Carbon_Metabolism

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000051.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000051.git@20140916`


# Model Notes
The model reproduces Figures 4,5 and 6 of the publication. The analytical
functions for cometabolites Catp, Camp, Cnadph, and Cnadp slightly differ from
the equations given in the paper. These changes were made in consultation with
Dr. Christophe Chassagnole and are essential for reproducing the figures. The
dependency of the rate of change of extracellular glucose concentration on the
ratio of biomass concentration to specific weight of biomass (Cx*rPTS/Rhox) is
taken into account by appropriately adjusting the stoichiometries of the
species involved in the phosphotransferase system (rPTS). The rmax values for
the various reactions are obtained from experiments and are not provided in
the paper. However, these were personally communicated to the JWS repository.
The model has been successfully tested on MathSBML.

** [SBML](http://www.sbml.org/) level 2 code generated for the JWS Online project by Jacky Snoep using [PySCeS](http://pysces.sourceforge.net/)   
Run this model online at
[http://jjj.biochem.sun.ac.za](http://jjj.biochem.sun.ac.za/)  
To cite JWS Online please refer to: Olivier, B.G. and Snoep, J.L. (2004) [Web-
based modelling using JWS
Online](http://bioinformatics.oupjournals.org/cgi/content/abstract/20/13/2143)
, Bioinformatics, 20:2143-2144 **

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


