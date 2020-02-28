# NSF_COA_GooSchol_parser

Jupyter notebooks for parsing your coauthorship list for NSF COA purposes.

Currently there are two notebooks:

## parse_scholar_authors.ipynb

This one just parses the authors list from a Google Scholar CSV export. 

## NSF_COA_affiliation_tool.ipynb 

This one takes a list of PubMed IDs and queries PubMed for the associated authors and their affiliations.

It also provides a guided interface for parsing organization and department out of the affiliation string. This is the one I ultimately ended up using.

In principle it should be possible to use a Google Scholar export to query PubMed directly without the intermediate PMID step, but for whatever reason I wasn't able to get consistent results using the the [Title] search parameter via the PubMed API. 