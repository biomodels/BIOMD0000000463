# BIOMD0000000463: MODEL1307270000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000463.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000463.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000463 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Heldt2012 - Influenza Virus Replication

The model describes the life cycle of influenza A virus in a mammalian cell
including the following steps: attachment of parental virions to the cell
membrane, receptor-mediated endocytosis, fusion of the virus envelope with the
endosomal membrane, nuclear import of vRNPs, viral transcription and
replication, translation of the structural viral proteins, nuclear export of
progeny vRNPs and budding of new virions. It also explicitly accounts for the
stabilization of cRNA by viral polymerases and NP and the inhibition of vRNP
activity by M1 protein binding. In short, the model focuses on the molecular
mechanism that controls viral transcription and replication.

This model is described in the article:

[Modeling the intracellular dynamics of influenza virus replication to
understand the control of viral RNA
synthesis.](http://identifiers.org/pubmed/22593159)

Heldt FS, Frensing T, Reichl U.

J Virol.

Abstract:

Influenza viruses transcribe and replicate their negative-sense RNA genome
inside the nucleus of host cells via three viral RNA species. In the course of
an infection, these RNAs show distinct dynamics, suggesting that differential
regulation takes place. To investigate this regulation in a systematic way, we
developed a mathematical model of influenza virus infection at the level of a
single mammalian cell. It accounts for key steps of the viral life cycle, from
virus entry to progeny virion release, while focusing in particular on the
molecular mechanisms that control viral transcription and replication. We
therefore explicitly consider the nuclear export of viral genome copies
(vRNPs) and a recent hypothesis proposing that replicative intermediates
(cRNA) are stabilized by the viral polymerase complex and the nucleoprotein
(NP). Together, both mechanisms allow the model to capture a variety of
published data sets at an unprecedented level of detail. Our findings provide
theoretical support for an early regulation of replication by cRNA
stabilization. However, they also suggest that the matrix protein 1 (M1)
controls viral RNA levels in the late phase of infection as part of its role
during the nuclear export of viral genome copies. Moreover, simulations show
an accumulation of viral proteins and RNA toward the end of infection,
indicating that transport processes or budding limits virion release. Thus,
our mathematical model provides an ideal platform for a systematic and
quantitative evaluation of influenza virus replication and its complex
regulation.

With the current parameter set, the model reproduces an infection at a
multiplicity of infection (MOI) of 10. Figure 2A of the paper is reproduced
here, with parameters kDegRnp and kSynP changed to zeros.

Initial conditions and parameter changes that were used to obtain specific
figures in the article can be found in Table A2.

The model has the correct value for kAttLo as 4.55e-04. The value of this
parameter mentioned as 4.55e-02 in Table 1 of the paper is incorrect. This is
checked with the author.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[MODEL1307270000](http://identifiers.org/biomodels.db/MODEL1307270000) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


