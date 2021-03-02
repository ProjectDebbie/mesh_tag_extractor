# Mesh tag extractor

The code takes a medline format collection of records downloaded from PubMed (e.g. using the 
[Ebot](https://www.ncbi.nlm.nih.gov/Class/PowerTools/eutils/ebot/ebot.cgi) tool) and returns a data frame with PMID, date and mesh tags for each record in the file. 

It is made of two functions:

* The first function convert the medline file ('refs') into multiple text files of individual abstracts, stored in 'folder'. 

* The second function extract PMID, date and MESH tags from each abstracts and generates a table in .csv file 


### Prerequisites

Python 3+


## Authors

**Osnat Hakimi** 


## License

This project is licensed under the GNU License - see the [LICENSE](LICENSE) file for details

## Funding

This project has received funding from the European Union’s Horizon 2020 research and innovation programme under the Marie Sklodowska-Curie grant agreement No 751277

