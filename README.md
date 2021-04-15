# Colour maps for fisheries acoustic echograms

## Introduction

This repository contains supplementary code and data for the paper
*Colour maps for fisheries acoustic echograms* (in press). `DOI:
10.1093/icesjms/fsz242`

All software is written in Julia 1.6.0 and made available as Jupyter
notebooks:

[Colour maps](colour-maps.ipynb)

[Echograms](echograms.ipynb)

[Which Blair Test](which-blair-test.ipynb)

[Colour map assessment methods](assessment.ipynb)

## Instructions

Clone the directory from github and `cd` into it. Run Julia. From the
package menu, `] activate .`. Then `using IJulia` and
`notebook(dir=".")`.

## Acknowledgements

The Krill ball - Sample Simrad EK60 echo sounder data is courtesy of
British Antarctic Survey and is licensed under the terms of the
Creative Commons Attribution 4.0 International License. The original
is available via [GitHub](https://github.com/bas-acoustics/krill-ball)

The image of Tony Blair, adapted for our experiments, is courtesy of
the World Affairs Council and is licensed under the terms of the
Creative Commons Attribution 2.0 Generic license. The original is
available via
[Flickr](https://www.flickr.com/photos/wacphiladelphia/6950750764/)

Our thanks to the officers, crew and scientists onboard the RRS James
Clark Ross for their assistance in collecting the data. Data
collection was funded as part of the Ecosystems Programme at the
British Antarctic Survey, Natural Environment Research Council, a part
of UK Research and Innovation.

This work was supported by the Natural Environment Research Council grant
NE/N012070/1.

## History

20210414 reb Updated for Julia 1.6.0
