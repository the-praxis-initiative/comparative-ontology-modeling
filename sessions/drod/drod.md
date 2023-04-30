# Modular Ontology Modeling

## Overview

An example of an ontology developed with this approach is the [Hydro Foundational Reference Ontology (HyFO)](https://www.semanticscholar.org/paper/Toward-A-Foundational-Hydro-Ontology-For-Water-Data-Brodaric-Hahmann/8b3ff70ff09ff36ea7105227551a2bc9ef36dadf) that has been shown to generalize various ontologies in the water domain, such as GWML2 or HY_Features,  as dicussed in: [Hahmann and Stephen: Using a hydro-reference ontology to provide improved computer-interpretable semantics for the groundwater markup language (GWML2)](https://doi.org/10.1080/13658816.2018.1443751). More axiomatic details are also available in [Brodaric et al.: Water features and their parts](https://doi.org/10.3233/AO-190205).


The methodology emphasizes the identification and ontological grounding of key concepts, relationships and distinctions early in the development to come up with a robust, reusable and extensible design. 



## Objectives
In this session we will start designing a domain reference ontology motivated by the [PFAS Use Case](../../use-cases/contamination-use-case.md).
We will use a set of competency questions to identify and organize the key domain terms, refine the questions and terms, and ontologically ground them in some top-level concepts and there come up with a clearer understanding of the domain and how to model it. Only afterwards, we will identify ontologies and pattern that we can potentially reuse to speed up the implementation of the ontology. 


## Process
1. **Define the use case(s).**<br>
This is already done for us: [PFAS Use Case](../../use-cases/contamination-use-case.md).

2. **Define initial set of competency questions.**<br>Keep them specific.

3. **Identify key terms (concepts and relationships).**<br>Try to generalize them as appropriate for the domain.

4. **Refine (by rephrasing, elaborating or deconstructing) the compentency questions.**

5. **Use a coarse analysis to separate concepts from relationships and to gain clarity about the nature of the concepts.**<br>
This involves thinking of the concepts in terms of top-level ontological distinctions between, for example, material and immaterial objects (including information), objects and locations, objects vs. events/processes, objects and their dispositions, etc.  

5. **Identify the most central concept(s) and start relating them to other concepts.**<br>
This is essentially developing a high-level Entity-Relationship model for the domain. 

6. **Refine the central concepts taxonomically.**<br>
We want to not just build a taxonomy, but use this as an exercise to think about the _definiens_, that is, the criteria that distinguish one concept (class) from its more general concepts and its sister concepts
