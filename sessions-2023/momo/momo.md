# Modular Ontology Modeling

## Overview
Modular Ontology Modeling (MOMo) methodology is a pattern-based methodology which emphasizes the data integration. It makes heavy use of a schema diagram as the conceptual vehicle. An example is provided [here](./schema-diagrams/example/). Ontological analysis and formalization primarily occurs *afterward* as a part of adapting patterns to the use-case, generally by examining the data, but also with input from appropriate domain expertise. 

## Objectives
In this session we will create a modular ontology which serves the [PFAS Use Case](../../use-cases/contamination-use-case.md). In particular, we will follow the MOMo methodology to identify candidate patterns, adapt them to our use-case, conduct systematic axiomatization (as necessary), and assemble the modules, and serialize the final product.

## Process
1. **Define the use case(s).**<br>
This is already done for us: [PFAS Use Case](../../use-cases/contamination-use-case.md).
2. **Develop competency questions.**<br>
There are some already in that same file.
3. **Identify key notions.**
- Municipality, County, State -> Region
- Taking a Reading
- Measurement
4. **Match patterns to key notions.**
- Region -> [Spatial Object](https://github.com/kastle-lab/modular-ontology-design-library/tree/master/modl/spatial-object)
- Reading -> [Observation](https://github.com/kastle-lab/modular-ontology-design-library/tree/master/modl/observation), [Provenance](https://github.com/kastle-lab/modular-ontology-design-library/tree/master/modl/provenance)
- Measurement -> [Quantity](https://github.com/kastle-lab/modular-ontology-design-library/tree/master/modl/quantity)
5. **Instantiate the patterns to create modules.**
- [Region](./schema-diagrams/region)
- [Reading](./schema-diagrams/reading)
- [Measurement](./schema-diagrams/measurement)
6. **Systematically axiomatize each module.**
- [Region](./schemas/region-module.owl)
- [Reading](./schemas/reading-module.owl)
- [Measurement](./schemas/measurement-module.owl)
7. **Assemble the modules.**<br>
[All Together](./deliverables/overview.png)
8. **Review the final product.**<br>
[Final Schema](./deliverables/final.owl)
9. **Produce artifacts (e.g., documentation and serialization).**<br>
[Documentation](./deliverables/documentation.md)

## References & Resources
Here are some convenient links to tools, resources, and examples for use during the MOMo process.

### Modular Knowledge Graphs
* [Enslaved Hub](https://enslaved.org/)
* [KnowWhereGraph](https://knowwheregraph.org/)

### Pattern Resources
* [Axiom Patterns](https://daselab.cs.ksu.edu/sites/default/files/Expressibility_of_OWL_%20Axioms_with_Patterns.pdf)
* [MODL](https://github.com/kastle-lab/modular-ontology-design-library)
* [ontologydesignpatterns.org](https://ontologydesignpatterns.org/)

### Tools
* [yEd](https://yworks.com/yed) -- for (only) graph diagram editing
* [Protégé](https://protege.stanford.edu/) -- for `ttl` generation
* [CoModIDE](https://comodide.com/) -- arguably also a pattern resource, it provides a graphical canvas for Protégé with pattern support.

### Cooking Recipe Tutorial
* [Cooking Recipe Tutorial 1](https://daselab.cs.ksu.edu/publications/modular-ontology-modeling-tutorial)
* [Cooking Recipe Tutorial 2](https://daselab.cs.ksu.edu/publications/tutorial-modular-ontology-modeling-ontology-design-patterns-cooking-recipes-ontology)

### Educational Material
* [Introduction to Knowledge Engineering](https://github.com/kastle-lab/cs7810-intro-to-ke)<br>
This course is taught at Wright State University as an introduction to creating a knowledge graph (using MOMo), its schema, and materialization.
* [KGC Open Curriculum](https://github.com/KGConf/open-kg-curriculum)<br>
This is a broad (unfinished) set of articles relating to knowledge graphs.