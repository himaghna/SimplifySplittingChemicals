<h1 align="center">SimplifySplittingChemicals</h1> 
<h3 align="center">Simplify your train:test Splitting for Chemicals in Machine Learning</h3>

<p align="center">  
  <img alt="simsplitchemlogo" src="https://github.com/JacksonBurns/SimplifySplittingChemicals/blob/main/simsplitchem_logo.png">
</p> 
<p align="center">
  <img alt="GitHub Repo Stars" src="https://img.shields.io/github/stars/JacksonBurns/SimplifySplittingChemicals?style=social">
  <img alt="PyPI - Downloads" src="https://img.shields.io/pypi/dm/simsplitchem">
  <img alt="PyPI" src="https://img.shields.io/pypi/v/simsplitchem">
  <img alt="PyPI - License" src="https://img.shields.io/github/license/jacksonburns/simplifysplittingchemicals">
</p>

## Background

### Rational Splitting Algorithms
While much machine learning is done with a random choice between training/test/validation data, an alternative is the use of so-called "rational" splitting algorithms. These approaches use some similarity-based algorithm to divide data into sets. Some of these algorithms include Kennard-Stone, minimal test set dissimilarity, and sphere exclusion algorithms [as discussed by Tropsha et. al](https://pubs.acs.org/doi/pdf/10.1021/ci300338w) as well as the DUPLEX, OptiSim, D-optimal, as discussed in [Applied Chemoinformatics: Achievements and Future Opportunities](https://www.wiley.com/en-us/Applied+Chemoinformatics%3A+Achievements+and+Future+Opportunities-p-9783527806546). Some clustering-based splitting techniques have also been introduced, such as [DBSCAN](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1016.890&rep=rep1&type=pdf).

## Splitting Algorithms
 - Random
 - Kennard-Stone (KS)
 - Minimal Test Set Dissimilarity
 - Sphere Exclusion
 - DUPLEX
 - OptiSim
 - D-Optimal
 - Density-Based Spatial Clustering of Applications with Noise (DBSCAN)

## Online Documentation
[Click here to read the docuemtntation](https://jacksonburns.github.io/SimplifySplittingChemicals/)

### TODO List
- [ ] add directory strucure
- [ ] tests and methods signatures
- [ ] github actions
- [ ] literature search for splitting methods to implement

### Directory Structure
Directory structure
```
SimplifySplittingChemicals
│   README.md
|
└───simsplitchem
│   │   __init__.py
│   │   simsplitchem.py
│   │
│   └───samplers
│       │   __init__.py
|       |  abstract_sampler.py
|       |  random.py
|       |  max_min.py
|       |  kennard_stone.py
│   └───utils
│       │   __init__.py
│       │   AIMSIM_wrappers.py
│   
└───test
└───docs
└───examples
```
