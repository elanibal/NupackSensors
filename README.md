# NupackSensors: Designing Novel Toehold Sensors 

Toehold riboswitches are a de-novo designed regulators of gene expression afecting translation. They have been used in many aplications including biocomputing and biosensors for RNA viruses including ébola, ZIka, Norovirus, PVY, and many more.

This repository is a open tool for designing novel toehold sensors for a given RNA. The design methodology is implemented in a Jupyter notebook, which calls out to the NUPACK software to analyse RNA structures. 

## Dependencies

### NUPACK 3.0 

NUPACK is the primary technology being used, and can be downloaded from http://nupack.org/.

As NUPACK only runs reliably on Linux, we recommend that Windows users run via Windows Subsystem for Linux (WSL) 2, which we have verified to work without any problems. The documentation for WSL is here: https://docs.microsoft.com/en-us/windows/wsl/

### Python 3 / Jupyter

The methods are demonstrated in a Jupyter notebook. Once you have python 3 installed, you can install the requirements using 

`pip install -r requirements.txt`


## Fast prototyping Toehold Sensors in cell-free reactions

Once toehold sensors are designed, they can be fastlly screened in cell-free reactions, or PURE-based reactions, using PCR products, and In-vitro transcribed trigger RNAs. We Use LacZ output, which gives a colorimetrics change from yellow ( negative controls ) to purple. 

<div style="text-align:center">
  <img src="Results_1.jpg" width="300">
</div>

<img src="positive.jpg" width="900">


Here is a link to the protocol we use for making in-house low-cost cell-free reactions https://www.protocols.io/view/preparation-of-cell-free-rnapt7-reactions-kz2cx8e

## References

Most of the code shown here is built on the top of an app from the iGEM group EPFL (2017) http://2017.igem.org/Team:EPFL/Results/Toehold.

The scoring metrics for the designs were taken from  Ma, D. et al.  (Low-cost detection of norovirus using paper-based cell-free systems and synbody-based viral enrichment. Synth.  Biol.3, ysy018 (2018))
