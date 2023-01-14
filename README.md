# data-mining-insects-of-guam

## Background
The objective of this project was to extract biodiversity data from legacy literature namely the 40 plus chapters in [Insects of Guam I](http://hbs.bishopmuseum.org/pubs-online/pdf/bull172.pdf) and [Insects of Guam II](http://hbs.bishopmuseum.org/pubs-online/pdf/bull189.pdf) published by the Bishop Museum in 1942 and 1946 respectively. These chapters are publicly available for download from the Bishop Museum web site. Data mining was greatly facilited by use of the Golden Gate Imagine software developed and maintained by Plazi. An automated workflow was developed by Plazi collaborators in Brazil to automated initial mark up of each chapter. Mark-up was later refined by manual parsing of material citations sections by collaborators at the University of Guam and Cornell University.

## Results
### Data products
#### Biodiversity Literature Respository

##### Book sections

Example: 

Light, S. F. (1946). Isoptera of Guam. In Insects of Guam II (pp. 9–9). Bernice P. Bishop Museum. https://doi.org/10.5281/zenodo.5160243

##### Taxonomic treatments

Example:

Light, S. F. (1946). Cryptotermes hermsi Kirby. In Isoptera of Guam, pp. 9 in Insects of Guam II (p. 9). Bernice P. Bishop Museum. https://doi.org/10.5281/zenodo.5208360

Download [treatment.html](https://zenodo.org/record/5208360/files/treatment.html?download=1)

Download [Plazi XML](https://zenodo.org/record/5208360/formats?mimetype=application%2Fvnd.plazi.v1%2Bxml)

#### GBIF

##### Dataset

https://www.gbif.org/dataset/5f279ac2-63c6-4bd8-be9e-0e3d82b73ab2

Example:

https://www.gbif.org/dataset/5f279ac2-63c6-4bd8-be9e-0e3d82b73ab2

Light S F, carolina (1946). Isoptera of Guam. Plazi.org taxonomic treatments database. Checklist dataset https://doi.org/10.5281/zenodo.5160243 accessed via GBIF.org on 2023-01-14. 

### Example Use Case: Insects Associated with Glochidion

[Table of insects associated with **Glochidion**](https://aubreymoore.github.io/data-mining-insects-of-guam/get_ecological_relationships/glochidion.html)

## TO DO

[Status report](https://aubreymoore.github.io/data-mining-insects-of-guam/validator2/status_report.html)

[Anthribidae: validation report before final edit](https://aubreymoore.github.io/data-mining-insects-of-guam/MatCit-Validator/anthribidae_before_final_edit.htmob
[Anthribidae: Understanding the validation (YouTube screencast)](https://youtu.be/FM-fHQhlIT4)

[Anthribidae: Editing matCit annotations (YouTube screencast)](https://youtu.be/NfRHdKfv7CQ)

[GitHub Pages served by this site](https://aubreymoore.github.io/data-mining-insects-of-guam/)

[Table of datasets extracted from Guam I and II](https://aubreymoore.github.io/data-mining-insects-of-guam/data/dataset-list.html)

## MatCit-Validator
* code (Jupyter notebook): [MatCit-Validator.ipynb](https://github.com/aubreymoore/data-mining-insects-of-guam/blob/main/MatCit-Validator/MatCit-Validator.ipynb)
* example input file: [example.xml](https://github.com/aubreymoore/data-mining-insects-of-guam/blob/main/MatCit-Validator/example.xml)
* example report output file: [example.html](https://aubreymoore.github.io/data-mining-insects-of-guam/MatCit-Validator/example.html)
