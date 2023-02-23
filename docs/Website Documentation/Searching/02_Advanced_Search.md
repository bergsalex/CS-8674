# Advanced Search
GeneWeaver’s search is performed using the Sphinx search engine. As a result, the search box accepts Sphinx-based shortcuts.

The words **OR** and **NOT** are translated automatically into sphinx operators "`|`" and "`-`" respectively.

Currently, defined field names are:

- GeneSet Metadata: `@name_`, `@description_`, `@label_`, `@attribution_`
- Publication Metadata: `@pub_authors_`, `@pub_title_`, `@pub_abstract_`,` @pub_journal_`, `_@pmid_`
- Group-Specific Access: `_@group_`
    - names of groups shared with (use quotes if necessary), or “Public”/“Private”
- All Gene Identifiers and Aliases: `_@gene_`
    - Does not currently map to microarray probes or homologous genes
- Ontology Terms: `_@term_`
    - includes unique ID, name, and term description
- Species: `@species_`, `@taxid_`
    - scientific name, or NCBI taxid (9606=human, 10090=mouse, etc)

## Example Search Terms

- `alcohol preference`
- or, more precise: `alcohol preference -QTL`
- or, even more precise: `alcohol preference -QTL @species rattus`

### Search all fields for striatum and gene Mobp:

- `MA:0000891 Mobp`
- or, more precise: `@term MA:0000891 @gene Mobp`

## Filtering Search Results
There is a filter section on the left side of the page.
