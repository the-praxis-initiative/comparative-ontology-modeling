# Same Data; Different Model (SDDM 2026)

## Abstract
Ontologies dictate how data are related to each other, acting as the blueprint of a specific use-case. Hence, different ontology engineering methods exist to serve those use-cases. Selecting an appropriate methodology is crucial; the modeling choices we make shape what the data can express and how concepts are grouped together. Therefore, in terms of exploring said appropriate methodology, it becomes important to take a look on how the same underlying data behave when modeled through different approaches. By comparing distinct ontology engineering methods, we can observe how hierarchies form, how constraints change, and how these differences affect interpretability and knowledge organization. Therefore, we propose a half-day tutorial in order to compare and visualize the results of two modeling techniques: the Linked Open Terms (LOT) methodology and the eXtreme Design with Content Ontology Design Patterns (XD) methodology, while also investigating how an LLM falls into the process.

---

## Schedule (3 hours)

1. **Overview & Methodological Context** (20 minutes)  
   Introduction to ontology engineering, motivation for comparative modeling, overview of LOT, XD, and BFO, and explanation of the dataset and evaluation workflow.

2. **Session 1 — Linked Open Terms (LOT) + Chowlk** [^1]

   [Session](./sessions/LOT/) (40 minutes)  
   

3. **Session 2 — Basic Formal Ontology (BFO)** 
   
   [Session](./sessions/bfo/bfo.md) (40 minutes)  


4. **Coffee Break / Informal Discussion** (30 minutes)


5. **Session 3 — eXtreme Design (XD)**    

   [Session](./sessions/xd/xd.md) (60 minutes)  
  
   
6. **Comparative Analysis, Embeddings & Discussion** (30 minutes)  
   Discussion on KGE construction and dimensionality reduction for visuals of the results. Closing remarks and takeaways.

---

## Organizers
- Antrea Christou  
- Cogan Shimizu  
- Davide Di Pierro  
- Danai Symeonidou  
- Lylia Abrouk  

---

## Instructors & Session Leads
- Davide Di Pierro
   - Davide Di Pierro is a postdoc researcher at the Université de Montpellier, France. His current research interests concern Ontology Construction, Linked Data, and Linked Data applications. Throughout his career, he also worked on graph databases, modelling OWL-compliant schemas for graph databases, automated reasoning, and software engineering for medical applications. 
   
- María Poveda-Villalón — Linked Open Terms (LOT) 
    - Dr. María Poveda-Villalón is an associate professor at the Artificial Intelligence Department of the Universidad Politécnica de Madrid and is also 
    part of the Ontology Engineering Group research lab. Her research activities focus on Ontological Engineering, Ontology Evaluation, Knowledge Representation, and the Semantic Web. She has contributed to the ontology engineering field by developing methodologies like Linked Open Terms and tools like OOPS! (Ontology Pitfall Scanner!) 
    and Chowlk, which have been broadly adopted by the community. She has worked in a number of Spanish and European research projects like VICINITY, AURORAL, COGITO, BIMERR, OntoCommons, etc.

- Andrea Giovanni Nuzzolese — eXtreme Design (XD) 
   - Andrea G. Nuzzolese is a Researcher at the Semantic Technology Laboratory (STLab) of the National Research Council (CNR) in Rome, Italy. His research interests concern Knowledge Extraction, Ontology Design Patterns, Linked Data, and the Semantic Web. He has been a researcher in the EU funded projects IKS% (Interactive Knowledge Stack), HACID (Hybrid Human Artificial Collective Intelligence in Open-Ended Domains), and WHOW (Water Health Open knoWledge), and the main developer of Apache Stanbol software stack, which provides a set of reusable components for semantic content management.

- Anna Sofia Lippolis — eXtreme Design (XD)  
   - Anna Sofia Lippolis is a PhD candidate at the University of Bologna, Italy, and is affiliated with the CNR Institute for Cognitive Sciences and Technologies. Her research interests span from the investigation of LLMs for ontology engineering-related tasks to cultural analytics and the more philosophical side of computational linguistics. She has been involved in the %EU funded 
    WHOW project.  

- John Beverley — Basic Formal Ontology (BFO)  
   - John Beverley is presently an Assistant Professor at the University at Buffalo and Co-Director of the National Center for Ontological Research. Throughout his research, he has worked with numerous groups on curating, creating, and applying knowledge representation artifacts to address semantic interoperability challenges. His work has supported efforts to identify vaccine and drug treatment options for COVID-19, update the widely used Infectious Disease Ontology, develop the Virus Disease Ontology extension, and create the Coronavirus Infectious Disease Ontology that extends from it. He has also worked extensively on Basic Formal Ontology (ISO/IEC 21838-2), which is used in the Open Biological and Biomedical Ontologies, the Industrial Ontologies Foundry, and the Common Core Ontologies suite. His ontology research both informs and is informed by his work in natural language semantics, analyses of epistemic injustices arising in healthcare settings, and narrative themes for meaning-making near the end of life.

---

[^1]: This work was supported by the grant "SOEL: Supporting Ontology Engineering with Large Language Models''  PID2023-152703NA-I00 funded by MCIN/AEI/10.13039/501100011033 and by “ERDF/UE”. 
