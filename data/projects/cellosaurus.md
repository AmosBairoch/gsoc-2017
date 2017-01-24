
##### Rationale

The cellosaurus is a knowledge resource on cell lines. It attempts to describe all cell lines used in biomedical research.

![Cellosaurus](https://media.licdn.com/mpr/mpr/AAEAAQAAAAAAAAVkAAAAJDQ4M2JmMzlmLTBkY2UtNGU4MC1hMjlhLTk1OTdmY2Y4ZTBhZA.jpg)

It is available on the SIB ExPAsy server (http://web.expasy.org/cellosaurus/)

##### Approach

Two enhancements should be carried out concerning the [Cellosaurus]:

-	Development of a Web-based tool to compare a user entered STR Marker profile for a cell line with all the STR marker data stored in the Cellosaurus. The program would run an algorithm similar to that described in [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3772516/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3772516/)

-	 Development of a Wikidata "bot" (https://www.wikidata.org/wiki/Wikidata:Bots) to enter some of the data stored in the Cellosaurus into Wikidata. The exact specification of the mapping of Cellosaurus data into Wikidata properties/clains and statements is being finalized. The bot would be ran at every release of the Cellosaurus to update the existing Wikidata cell line concepts and create new ones for cell lines newly entered at each release.

##### Challenges

- For the first part: know how to write web page/formulars, understand the algorithm and implement it using the data available in the XML file of the Cellosaurus (for the XSD see ftp://ftp.expasy.org/databases/cellosaurus/cellosaurus.xsd)
- For the second part: understand the Wikidata data structure and either edit an existing bot or creat one from scratch. 

##### Requirements

- The student must have read the publication and understood the algorithm.
- Read the specifications for what data in the Cellosaurus will be imported to Wikidata. The specification document is being finalized and will be available soon.
