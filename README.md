# Goldstonian Concordance Bible Corpus Dataset

Author: Justin Goldston, PhD

## Overview

This dataset contains the structured data layer of the Goldstonian Concordance Bible (GCB), a digital humanities project mapping relationships between biblical texts, commentary nodes, thematic references, and teaching materials.

The dataset is designed for research in:

- digital humanities
- biblical studies
- computational theology
- knowledge graph development
- natural language processing

This repository represents the archival dataset layer.  
The full project infrastructure, commentary volumes, and additional materials are available at:

https://github.com/GoldstonianConcordanceBible

## Dataset Contents

books.csv  
List of books included in the dataset.

passages.csv  
Segmented passages by book, chapter, and verse.

cross_references.csv  
Structured relationships between passages.

themes.csv  
Theological themes associated with passages.

video_index.csv  
Links between scripture passages and teaching videos.

commentary_nodes.json  
Commentary entries associated with passages.

## Intended Use

This dataset is intended for research, educational, and computational analysis purposes.

## Graph Dataset

The corpus includes a cross-reference network dataset suitable for graph analysis.

File: cross_reference_network.csv

This dataset represents a directed network where nodes are scripture passages and edges represent interpretive relationships.

Potential uses include:

- knowledge graph research
- computational theology
- network analysis
- digital humanities studies

## Machine Learning Corpus

The dataset includes a JSONL corpus file:

passages_corpus.jsonl

Each record represents a scripture passage node and may be used for:

• natural language processing experiments
• knowledge graph generation
• text classification
• digital humanities analysis