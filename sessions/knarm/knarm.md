# KNowledge Acquisition and Representation Methodology (KNARM)

## Overview
KNowledge Acquisition and Representation Methodology (KNARM) allows domain experts and knowledge engineers to build useful, consistent, concordant knowledge graphs and ontologies formalizing domain data and knowledge in a systematic way using modular ontology architecture and systematically deepening modeling for domain knowledge. It is designed to help with the challenge of acquiring and representing knowledge in a systematic, semi-automated way. This methodology aims at acquiring knowledge from data scattered in different databases and ontologies, combining them in a meaningful fashion that is understandable by humans and machines by effectively combining human and machine capabilities. In this way, we attempt to allow users to understand, query, and analyze their data better.

## Objectives
In this session, we will go over the steps of creating a modular ontology using KNARM which serves the [PFAS Use Cases](../../use-cases/contamination-use-case.md). At each step of the methodology, we will discuss what was done, and how it could be improved using systematically deepening modeling and using a systematic approach to building the knowledge graph backend with a semi-automated approach using a modular architecture.

## Process
1. **Sub-language Analysis**<br>
This is already done for us: [PFAS Use Case](../../use-cases/contamination-use-case.md).
2. **Unstructured Interview**<br> 
This step combined with the previous step is all about understanding the questions better.
3. **Sub-Language Recycling**
Identify vocabularies and patterns that may have already been generated to avoid duplication of efforts.
4. **Meta Data Creation and Knowledge Modeling**
[Based on the questions and sub-language identified, can we create our modeling of the data? Questions to consider: how deep do I go in my modeling? What aspects are modeled in T-Box, and what’s modeled in A-Box?](./deliverables/PFASWaterQuality_modules.pdf)
5. **Structured Interview**
Use the model to retrieve data from domain experts in a FAIR way from the start.
6. **Knowledge Acquisition Validation**
Ensure that we can still answer the complex questions we had at the beginning..
7. **Database Formation**<br>
[Opt for sustainable data storage and create a database backend.](./deliverables/graph.png)
8. **Semi-Automated Ontology Building**<br>
[Use tools like Robot or write your own scripts for building the owl files from the database backend following a modular architecture and systematically deepening modeling outlined in KNARM.](./deliverables/)
9. **Ontology Validation**<br>
Ultimate test for your ontology is to put it in use via applications, community, and algorithms and evaluate performance. Keep in mind that KNARM follows an agile approach and believes in improving the knowledge graphs based on community needs and changes to the vocabularies in the backend.

## References & Resources
Here are some convenient links to tools, resources, and examples to use while implementing your knowledge graphs using KNARM.

### Ontologies Built using KNARM
* [BioAssay Ontology](https://bioportal.bioontology.org/ontologies/BAO)
* [Drug Target Ontology](https://bioportal.bioontology.org/ontologies/DTO)
* [FDC Ontology](https://fdc.nal.usda.gov/)

### Tools that use ontologies using KNARM ###
* [BioHarmony Annotator](https://www.bioassayexpress.com/)
* [OntoloBridge](https://github.com/OntoloBridge/ontolobridge-project)
* [Pistoia Alliance DataFAIRy Project](https://www.pistoiaalliance.org/projects/current-projects/datafairy-bioassay-annotation/)


### Tools

* [Protégé](https://protege.stanford.edu/) -- for file generation and manual steps
* [Robot](http://robot.obolibrary.org/report) -- a command-line tool for creating .owl files in a semi-automated way.
* [Neo4j](https://neo4j.com/) -- for the graph database backend

### Educational Material
* [Knowledge Acquisition and Representation Methdology (KNARM) and its Applications (KARMA)](https://scholarship.miami.edu/esploro/outputs/991031447865202976)<br>
