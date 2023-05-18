# textbook-kgc

This repository contains the python scripts as well as the input TEI model, html and word files of the textbook. Preliminary extraction results and sample enrichment results can be found in the results folder. Due to size, the full enrichment results were not uploaded but can be retrieved using Import_WikiData.ipynb script.

/data

- docx: input for spaCy pipeline
- html: input for GCP pipeline (Neo4j)
- teiModel.xml: input for TEI pipeline

/src

- XMLparsing.ipynb: output triples for TEI pipeline
- construction_spaCy_TEI_GCP.ipynb: output preliminary KG/entities for all three approaches, including spaCy KG extraction.
- Import_WikiData.ipynb: output enriched triples from Wikidata

/results

- KG_extraction: triples from spaCy, TEI and entities from GCP
- enrichment_example: triples from Wikidata for spacy and GCP on term "cloud computing"

Spring 2023
