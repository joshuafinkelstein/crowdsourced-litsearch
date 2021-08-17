# crowdsourced-litsearch
Offers an alternative approach for finding articles by rank listing common references within a set of articles. In that way, a single well regarded article can serve as the basis for a methodical literature search.

# Description
The algorithm starts by using a set of references from a single article. It is best if that article has been cited in other articles or has highly reputable authors. The references from that initial article are used to generate a list of secondary references (all the articles referenced within the initial set of references). From that list, the most commonly cited articles are displayed each with a link and associated metadata.

# Getting Started
Install Required Dependencies
`pip install habanero`

This will allow access to the Crossref API. 
