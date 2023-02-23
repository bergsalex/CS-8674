# Curation Standards

Secondary functional genomics data consists of the results of analyzed experiments in functional genomics. In contrast
to primary data stores such as Gene Expression Omnibus (GEO) in which raw experimental data are stored, a secondary data
store attempts to collect the results of experimental design and decision-making process of the researcher so that one
may interpret and integrate the gene set centered outcomes of the studies. Controlling the quality and validity of the
large-scale analysis of secondary data requires the enforcement of interpretable standards for gene set construction and
description. 

GeneWeaver’s use of discrete analysis eliminates many barriers to the integration of heterogeneous data
sets across species and experiments. However, it is important for users to be able to rapidly interpret the nature of
gene sets retrieved from the site, requiring a minimal standard for metadata associated with secondary data. For this
purpose, both unstructured textual descriptions of the data and structured ontology annotations to the terms in these
descriptions are used to define gene sets.

In the interest of encouraging submission we are cautious not to be too prescriptive or burdensome to users, but rather 
to provide guidelines on standards used by internal curators to assess data quality and clarity to enable rapid 
acceptance of community submissions to the data repository.

## Curation Tiers
...


## General Definitions
!!! abstract "Gene Set Name" 
    A brief title for the gene set, approximately sentence length, that should provide a clear and concise description 
    of the contents of a gene set interpretable to most users of GeneWeaver, but with sufficient detail to satisfy a 
    domain expert.  This is the major gene set name that is displayed in all search results, project directory and table
    views of analysis results. Standards for specific gene set types are given in the following section.

!!! abstract "Gene Set Figure Label" 
    A brief 23-character abbreviation to facilitate recognition of the gene set in a graph or other display.

!!! abstract "Gene Set Description"
    A detailed description of the gene set, including rules for its construction, experimental methods and analyses used
    to generate data, anatomical terms, and traceable references to source data including accession information and 
    date. Abbreviations should be avoided.

!!! abstract "Ontology Annotations"
    Relevant terms from Disease Ontology, Mammalian Ontology and other OBO ontologies supplied by curators or identified
    through the application of the NCBO Annotator to textual descriptions including publication abstracts.

!!! abstract "Publication Information" 
    PubMed ID, title, authors, publication information and full-text of the abstract.


## Standards for Common Gene Set Types
...