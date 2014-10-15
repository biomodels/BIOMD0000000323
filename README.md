# BIOMD0000000323: Kim2011_Oscillator_SimpleIII

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000323.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000323.git@20140916`


# Model Notes


This a model from the article:  
**Synthetic in vitro transcriptional oscillators.**   
Kim J, Winfree E _Mol. Syst. Biol._ 2011 Feb 1;7:465.
[21283141](http://www.ncbi.nlm.nih.gov/pubmed/21283141) ,  
**Abstract:**   
The construction of synthetic biochemical circuits from simple components
illuminates how complex behaviors can arise in chemistry and builds a
foundation for future biological technologies. A simplified analog of genetic
regulatory networks, in vitro transcriptional circuits, provides a modular
platform for the systematic construction of arbitrary circuits and requires
only two essential enzymes, bacteriophage T7 RNA polymerase and Escherichia
coli ribonuclease H, to produce and degrade RNA signals. In this study, we
design and experimentally demonstrate three transcriptional oscillators in
vitro. First, a negative feedback oscillator comprising two switches,
regulated by excitatory and inhibitory RNA signals, showed up to five complete
cycles. To demonstrate modularity and to explore the design space further, a
positive-feedback loop was added that modulates and extends the oscillatory
regime. Finally, a three-switch ring oscillator was constructed and analyzed.
Mathematical modeling guided the design process, identified experimental
conditions likely to yield oscillations, and explained the system's robust
response to interference by short degradation products. Synthetic
transcriptional oscillators could prove valuable for systematic exploration of
biochemical circuit design principles and for controlling nanoscale devices
and orchestrating processes within artificial cells.

**Notes:**

The paper describes 7 models (MODEL1012090000-6) and all these are submitted
by the authors. This model (MODEL1012090001) corresponds to the Simple model
of the three-switch ring oscillator (Design III). The model reproduces figure
6 (central figures) of the reference publication. The time is rescaled by
s=v_d/K_I*t where K_I=0.333 and v_d=1 (for alpha = 1) and v_d=0.5 (for alpha =
0.5). i.e. For alpha = 1, s = 0.003 * t (roughly 10 unitless time = 1hr; the
time-course should be run for 60 timeunits (6hrs) to get figure 6a). For alpha
= 2, s= 0.0015 * t (roughly 5 unitless time = 1hr; the time-course shoue be
run for 100 timesunits (20hrs) to get figure 6b).

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


