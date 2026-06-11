**Scegli la lingua / Choose your language**

[![Italiano](https://img.shields.io/badge/italiano-blue?style=for-the-badge)](README.md)
[![English](https://img.shields.io/badge/english-red?style=for-the-badge)](README.en.md)

# Semantic assets for the *Portal of sources for the history of the Italian Republic*

![Portal of sources for the history of the Italian Republic.](./img/logo_pfsri.png "Portal of sources for the history of the Italian Republic")

## Overview

This repository hosts the **ontology modules** that make up the **ontology network** designed and developed as part of the initiative to build the [Portal of sources for the history of the Italian Republic](https://portalefontirepubblicaitaliana.cnr.it/) (in Italian, *Portale delle fonti per la storia della Repubblica italiana*).

The portal is built upon data structured as a **semantic knowledge graph**, following the Linked Open Data paradigm. The ontology network defines the reference semantic models for representing and interlinking people, organizations, events, archival resources, and all other entities relevant to the domain. These models provide the semantic foundation of the portal's knowledge graph, enabling the integration of data from heterogeneous sources and supporting their publication as **Linked Open Data**.

### About the Portal

The [Portal of sources for the history of the Italian Republic](https://portalefontirepubblicaitaliana.cnr.it/) is a project coordinated by the **Italian National Research Council (CNR)** and aimed at providing a standards-based, interoperable digital infrastructure designed to aggregate, harmonise, and expose a distributed corpus of heterogeneous resources representing the body of sources related to the political and institutional history of Italy's republican period.

The portal integrates and harmonises these diverse datasets through the definition of a reference ontology network, making them accessible within the context of both public and private archives documenting aspects of the history of the Italian Republic. These resources are interoperable and machine-readable, and include archival documents as well as complementary entities such as organisations, legislative acts, and other materials related to the political context in which these documents were produced.

### Core data sources

Various institutions and public bodies (the Historical Archives of the Presidency of the Italian Republic, the Historical Archives of the Senate of the Italian Republic, the Historical Archives of the Italian Chamber of Deputies, and the Italian Central Archives of the State), together with a group of foundations and cultural institutes affiliated with the *Association of Italian Cultural Institutions* ([AICI](https://www.aici.it/)), have made available their portals, databases, and information systems providing descriptions and digitizations of parts of their archival holdings and domain data (also as Linked Open Data). These contributions have driven the design of the ontological models and the population of the knowledge graph supporting the portal.

Some of the reference data portals that have informed the ontology design process and constitute key data sources for specific domains within the portal’s knowledge graph include:
* [The open data portal of the Historical Archives of the Presidency of the Italian Republic](https://archivio.quirinale.it/aspr/)
* [The open data portal of the Italian Chamber of Deputies](https://dati.camera.it/en)
* [The open data portal of the Senate of the Italian Republic](https://dati.senato.it/)
* [The open data portal of the Italian Central Archives of the State](http://dati.acs.beniculturali.it/)

## Repository Structure

This repository is organized to support the full lifecycle of ontology engineering. For the ontology modules we follow a modular and explicit versioning pattern to ensure backward compatibility and stable URI resolution for the ontology network.

```text
assets
└── ontologies/                  # Root for all OWL-serialized ontology modules
    ├── [module-name]/           # e.g., IRHO, person, event, diary
    │   ├── v0.1/                # Specific version snapshot
    │   ├── v0.2/
    │   ├── ...
    │   ├── latest/              # Copy of the most recent stable release
    │   │   ├── module.owl       # OWL RDF/XML serialization
    │   │   ├── module.rdf       # RDF/XML serialization
    │   │   └── module.ttl       # Turtle serialization
    │   └── Grafici/             
    │       ├── module.graphml   # Source of the Grafoo diagram
    │       └── module.png       # Graffoo diagram
    └── ...
```

📂 [`ontologies/`](./ontologies)

It is the core of the repository with the **ontology modules**. Each module is partitioned by version. The `latest/` directory always contains the current stable release, including multiple serializations (Turtle, RDF/XML, etc.). Graphical representations are also provided in the form of [Graffoo](https://essepuntato.it/graffoo/) diagrams. These diagrams provide the formal visual mapping of classes, properties, and axioms, serving as the primary visual design reference.

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/3.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

Ontology modules and realted documentation are licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.

## Contributing and community engagement

We welcome contributions from domain experts and the Semantic Web community to help improve the ontology network. Anyone is free to contribute by identifying errors or inconsistencies, suggesting new terms, or proposing improvements to the models.

To ensure all changes are tracked and discussed transparently, we encourage using **GitHub Issues** as primary communication channel.

* **Report a Bug:** Notice an inconsistency in an OWL module or a broken link?
* **Suggest an Improvement:** Have an idea for a more descriptive property or a new class?
* **Request a Feature:** Need an extension to support a specific use case?

To contribute or ask your question, **[open a new issue](https://github.com/PortaleFontiRepubblica/assets/issues/new/choose)** in this repository. Please provide as much detail as possible.

## Governance and Maintenance

The ontologies in this repository were designed and developed by the Italian National Research Council, with a strong collaboration between:
* the **Institute of Cognitive Sciences and Technologies** ([CNR-ISTC](https://www.istc.cnr.it/)), primarily responsible for the knowledge engineering process
* the **Institute for Applied Mathematics and Information Technologies** ([CNR-IMATI](https://www.imati.cnr.it/make_home_page.php?language=ENG))
* the **Institute for the European Intellectual Lexicon and History of Ideas** ([CNR-ILIESI](https://www.iliesi.cnr.it/?lan=en))

To ensure that these assets remain a reliable foundation for the community:

* **Long-term maintenance:** CNR is committed to the long-term maintenance and sustainability of the semantic assets beyond the initial project lifecycle.
* **URI persistence:** All namespaces and identifiers are managed to ensure permanent resolution within the Linked Data ecosystem.
* **Institutional support:** As the host of the portal, CNR provides the institutional stability necessary to keep the underlying infrastructure fully operational.