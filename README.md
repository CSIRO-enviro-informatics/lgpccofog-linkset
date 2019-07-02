# LGPC / COFOG Linkset
This code repository contains a Linkset - a specialised Dataset linking objects in two other Datasets.

This Linkset contains [SKOS mapping properties](https://www.w3.org/TR/skos-reference/#mapping) between Concepts in the [AGIFT](http://linked.data.gov.au/def/lgpc) and Concepts in the [COFOG](http://linked.data.gov.au/def/cofog) vocabularies.

LGPC, "Local Government Purpose Classification" is an [Australian Bureau of Statistics (ABS)](https://www.abs.gov.au) a vocabulary of classifiers for use in the collection, analysis and dissemination of local government finance statistics in Australia.

COFOG, "Classification of the Functions of Government", is a [United Nations Statistics Division](https://unstats.un.org/unsd/iiss/Classification-of-the-Functions-of-Government-COFOG.ashx)-issued vocabulary used to "...distinguish between the individual and collective services provided by general government and identifies consumption expenditures that benefit individual households...".


## Linkset relations
This Linkset uses only [SKOS Mapping Properties](https://www.w3.org/TR/skos-reference/#mapping) to map between AGIFT & COFOG-A. Only the following properties are used:

* `skos:exactMatch`



## Repository Contents
This repository contains the following files and folders:

* [README.md](README.md) - this file
* [imports/](imports/) - background information: the LGPC & COFOG vocabularies as RDF (turtle) files
* [data.ttl](data.ttl) - this Linkset's links as an RDF (turtle) file
* [header.ttl](header.ttl) - this Linkset’s data.ttl header information, stored separately for ease of access
* [example-data.ttl](example-data.ttl) - 5 Statements from the Linkset for ease of access, in RDF (turtle) format, as per the main data file but none of the whole-of-Linkset information
* [example-data-unreified.ttl](example-data-unreified.ttl) - 5 Statements from the Linkset but flattened, 'unreified', for even easier use
* [methods/](methods/) - a folder containing the interim correspondences.xlsx file used for correspondence transpcription from the LGPC PDF document


## Rights & License
The content of this repository is licensed for use under the [Creative Commons 4.0 License](https://creativecommons.org/licenses/by/4.0/). See the [license deed](LICENSE) all details.

Please note:

The LGPC & COFOG-A vocabularies' content is copyright of the ABS, as per the notification in their source documents that reads:

> This work is copyright. Apart from any use as permitted under the Copyright Act 1968, no part may be reproduced by any process without prior written permission from the Commonwealth. Requests and inquiries concerning reproduction and rights in this publication should be addressed to The Manager, Intermediary Management, Australian Bureau of Statistics, Locked Bag 10, Belconnen ACT 2616, by telephone (02) 6252 6998, fax (02) 6252 7102, or email: <intermediary.management@abs.gov.au>.

The correspondences that constitute the links in this Linkset are considered part of the LGPC vocabulary and thus fall under the same rights notice.


## Contacts
*Technical contact:*  
**Nicholas Car**  
CSIRO Land & Water, Environmental Informatics Group  
<nicholas.car@csiro.au>
<http://orcid.org/0000-0002-8742-7730>
