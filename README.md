# BEACH-semantic-map

<p align="center">

[/TODO create a ZENODO DOI/]: #  (<a href="https://doi.org/10.5281/zenodo.17521899"><img alt="DOI: 10.5281/zenodo.17521900 " src="https://zenodo.org/badge/DOI/10.5281/zenodo.17521900.svg"></a>)
<a href="https://opensource.org/licenses/Apache-2.0"><img alt="Licence: Apache 2.0" src="https://img.shields.io/badge/Licence-Apache%202.0-blue.svg"></a>
<br>
<a href="https://github.com/alex-shpak/hugo-book"><img alt="Hugo" src="https://img.shields.io/badge/Hugo-hugo book-cd007b.svg"></a>
<a href="https://github.com/MaastrichtU-CDS/Flyover"><img alt="Flyover version 3.0+" src="https://img.shields.io/badge/Flyover%20Version-3.0+-purple"></a>
</p>
Semantic map of the data elements collected for BEACH.

## **What is the purpose of this repository?**

This repository contains the semantic map of the data elements collected for BEACH.  
The semantic map is in the form of a JSON-LD file and is used to facilitate:

- Interoperability across various datasets;
- OMOP CDM database creation.

## **How is this repository organised?**

The repository is organised as follows:
Every branch corresponds to a different participating organisations.  
As different datasets are added, new elements should be mapped for the given dataset in the organisation's branch.  
When new data elements are added to the schema, they can be merged into the different branches so that the
schema is consistent across organisations.
The differences should then be merged through these branches to make up a global semantic map in the main branch.

## **How can this repository be used?**

The JSON-LD file can be used in the [Flyover tool](https://github.com/MaastrichtU-CDS/Flyover).

[//]: # (## **How was this work funded?**)

[//]: # (TODO)
