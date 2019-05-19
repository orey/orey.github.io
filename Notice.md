# About GraphApps Turtle grammar

## Introduction

The GraphApps grammar was written to address several use cases:

  * The constitution of a grammar language for creating RDF triples from CSV files
    * Link: https://github.com/orey/scv2rdf
  * The creation of classes and properties to be able to enrich RDF graphs with information making them representable
    * Link: https://github.com/orey/rdfviz
    
## Version

Currently the GraphApps grammar version in use is `1`.

## Artifacts for the grammar language

Currently, only 2 datatypes are defined:

  * `<https://orey.github.io/graphapps-V1#Identifier>`
  * `<https://orey.github.io/graphapps-V1#Separator>`

The first grammar using those artifacts can be found [here](https://github.com/orey/csv2rdf/blob/master/grammars/semantic-grammar).

## Artifacts for the identification of nodes and edges

Two classes and two properties were defined in this area :

  * `<https://orey.github.io/graphapps-V1#Node>`
  * `<https://orey.github.io/graphapps-V1#Edge>`
  * `<https://orey.github.io/graphapps-V1#source>`
  * `<https://orey.github.io/graphapps-V1#target>`

The [rdfviz](https://github.com/orey/rdfviz) repo is using those artifacts to enrich the RDF files to make them visualizable as a graph.


