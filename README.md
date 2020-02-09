# my-parsers
Python parsers I've used for personal projects for processing outputs from MEME suite.

## FIMO
The package fimo_parser so far contains one module called GFF.py which parses fimo files by that name. I've found other GFF parsers were too burdensome or weren't properly interpreting motif hit locations. The module has a single class, GFF_Parse, which when given an appropriate filepath it will generate and store a pandas dataframe. The dataframe contains the following columns: name of scanned sequence, start position, end postion, strand orientation, motif id, found motif sequence and both q and p values of the hit.

## Prerequisites
The only imports are Pandas and regex.


## Author
Benjamin Clark 

BS Cell and Molecular Biology,
Concordia University

benjamin_r.clark@live.com
