# Mesh tag extractor

The code takes a medline list of records downloaded from PubMed (e.g. using the eBOT tool) and returns a .csv table with PMID, date and mesh tags for each record in the list. 



2. The first function convert this file into multiple text files of individual abstracts
3. The second function extract desired information contained in lines after specific tags (PMID, date and MESH tags)
4. The output file is a .csv table with the results recorded as per entry



### Prerequisites

Python 3+


## Authors

**Osnat Hakimi** 


## License

This project is licensed under the GNU License - see the [LICENSE.md](LICENSE.md) file for details
