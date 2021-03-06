# Computational Drug Discovery Process

Believe it or not, anyone can do computational drug design/discovery. Yes, even you! Below, I describe a simplified process for taking a receptor of choice and developing a model for a new drug. 

## Selecting a Protein Target 

This is usually up to the discretion of the user. Hopefully there is a crystal structure. If not, it might be possible to do some homology modeling. I will revisit this area in the future....

## Obtaining Protein Structure 

### Just Downloading It 

To find a receptor, the first thing you should probably do is check http://www.rcsb.org. These structures should be avaiable for download in .pdb format, which is universally used for working with 3D protein structures. 

### Homology Modeling 

(Project Idea: Writing script to download .pdb file of protein in PDB most closely related to sequence of amino acids) 

## Building a Small Molecule Database

In efforts to build a small molecule database, I will write a script to pull all molecules from PubChem that follow Lipinski's Rule of 5

Lipinski's Rule of 5:
* <= 5 Hydrogen Bond Donors 
* <= 10 Hydrogen Bond Acceptors 
* Molecular Mass <500 Daltons 
* Octanol-Water Partition Coefficient log(P) <= 5  

Large Chemical Databases: 
* https://pubchem.ncbi.nlm.nih.gov/ 
* https://www.ebi.ac.uk/chembl/index.php 
* https://www.drugbank.ca/ 
* (Information/More Resources: https://en.wikipedia.org/wiki/Chemical_database) 

PubChem Substances: 250,188,056

Lipinski's Rule of 5 Substance: 

In  an effort to be efficient in speed and time, it might be best to consolidate this set by selecting a subset of molecules that are representatitve of the larger set.  

## Building a Molecular Fragment Database 

TBA 

## Virtual High-Throughput Screening

### Ligand-Based

### Receptor-Based

## Lead Design

### Ligand-Based

### Receptor-Based 

## Lead Optimization

This is the process of taking a lead and chemically modifying it (e.g. exchanging functional group) so that it may bind better. 

I am currently working on a lead optimization research project under Dr. David Koes (see KoesGroup and LeadOptimization repositories for more info). 

# 

Resources: https://www.click2drug.org/index.html
