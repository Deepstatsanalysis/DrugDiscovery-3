# Computational Drug Discovery Process

## Selecting a Protein Target 

This is usually up to the discresion of the user. Hopefully there is a crystal structure. If not, it might be possible to do some homology modeling. I will revisit this area in the future....

## Building a Small Molecule Database

In efforts to build a small molecule database, I will write a script to pull all molecules from PubChem that follow Lipinski's Rule of 5

Lipinski's Rule of 5:
* <= 5 Hydrogen Bond Donors 
* <= 10 Hydrogen Bond Acceptors 
* Molecular Mass <500 Daltons 
* Octanol-Water Partition Coefficient log(P) <= 5  

PubChem Substances: 250,188,056

Lipinski's Rule of 5 Substance: 

(*Note: Octanol-Water measurement not included as that has to be experimentally determined*)

In  an effort to be efficient in speed and time, it might be best to consolidate this set by selecting a subset of molecules that are representatitve of the larger set.  

## Building a Molecular Fragment Database 

TBA 

## Virtual High-Throughput Screening

TBA 

## Lead Design

TBA 

## Lead Optimization

This is the process of taking a lead and chemically modifying it (e.g. exchanging functional group) so that it may bind better. 

I am currently working on a lead optimization research project under Dr. David Koes (see KoesGroup and LeadOptimization repositories for more info). 

# 

Resources: https://www.click2drug.org/index.html
