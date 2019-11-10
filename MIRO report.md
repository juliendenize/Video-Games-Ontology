MIRO – Minimum Information for Reporting of an Ontology


### A.1 Ontology name


 Video-games ontology, v1.0 


### A.2 Ontology owner

Julien Denize, Alexandre DAZAT

### A.3 Ontology license

Creative Commons Attribution 3.0 (CC BY 3.0) 


### A.4 Ontology URL

URL

### A.5 Ontology repository 

URL


### A.6 Methodological framework

|  | Specification |
|---|---|
| **Description:** | A name or description of the steps taken to develop the ontology. This should describe the overall organisation of the ontology development process. |
| **Importance:** | MUST |
| **Value:** | Methontology, On-To-Knowledge, Neon methodology. If no bespoke methodological framework was used, describe how the core activities of the ontology engineering lifecycle (such as ontology management, development and support) were addressed (http://onlinelibrary.wiley.com/doi/10.1002/047003033X.ch9/pdf). |


## B. Motivation

### B.1 Need

Single ontology ressource that enables users to search games in databases with fine-grained granularity regarding the platforms, people involved in developpement, genre. 


### B.2 Competition

The closest ontology to what we did can be found at the following URL : 
 
https://bartoc.org/en/node/18344

Besides, it mainly aims at encapsulating knowledge on events that happen in video gamees and information about players, whereas ours 

### B.3 Target audience

|  | Specification |
|---|---|
| **Description:** | The community or organisation performing some task or use for which the ontology was developed. |
| **Importance:** | MUST |
| **Value:** | The Gene Ontology is used by curators of gene products to describe the major functional attributes of those gene products to provide a common language across species for describing the molecular function, biological process and cellular location of gene products. |


## C. Scope, requirements, development community

### C.1 Scope and coverage

|  | Specification |
|---|---|
| **Description:** | The domain or field of interest for the ontology and the boundaries, granularity of representation and coverage of the ontology. State the requirements of the ontology, such as the competency questions it should satisfy. A visualisation or tabular representation is optional, but often helpful to illustrate the scope. |
| **Importance:** | MUST |
| **Value:** | From the Human Phenotype Ontology NAR 2013 article "human phenotypic abnormalities." https://academic.oup.com/nar/article-lookup/doi/10.1093/nar/gkt1026  |


### C.2 Development community

|  | Specification |
|---|---|
| **Description:** | The person, group of people or organisation that actually creates the content of the ontology. This is distinct from the Ontology Owner (above) that is concerned with the management of the ontology's development. |
| **Importance:** | MUST |
| **Value:** | The Gene Ontology is developed by the Gene Ontology Consortium. |


### C.3 Communication

|  | Specification |
|---|---|
| **Description:** | Location, usually URL,  of the email list and/or the issue tracking systems used for development and managing feature requests for the ontology. |
| **Importance:** | MUST |
| **Value:** | http://www.ebi.ac.uk/efo/submit.html |


## D. Knowledge acquisition

### D.1 Knowledge acquisition methodology

|  | Specification |
|---|---|
| **Description:** | How the knowledge in the ontology was gathered, sorted, verified, etc. |
| **Importance:** | MUST |
| **Value:** | Description of the source knowledge in the materials and method section of the article for The Software Ontology (SWO): a resource for reproducibility in biomedical data analysis, curation and digital preservation in JBMS 2014 https://jbiomedsem.biomedcentral.com/articles/10.1186/2041-1480-5-25 |


### D.2 Source knowledge location

|  | Specification |
|---|---|
| **Description:** | The location of the source whence the knowledge was gathered. |
| **Importance:** | SHOULD |
| **Value:** | Description of data gathered such as found in https://softwareontology.wordpress.com/2011/04/04/an-agile-ontology/. Other Values may include the outputs from workshops, curating the literature for a field, crowd sourcing input and so on. |


### D.3 Content selection

|  | Specification |
|---|---|
| **Description:** | The prioritisation of entities to be represented in the ontology and how that prioritisation was achieved. Some knowledge is more important or of greater priority to be in the ontology to support the requirements of that ontology. |
| **Importance:** | SHOULD |
| **Value:** | Description of the prioritisation process for the Software Ontology in https://softwareontology.wordpress.com/2011/04/04/an-agile-ontology/ |


## E. Ontology content

### E.1 Knowledge Representation language

|  | Specification |
|---|---|
| **Description:** | the knowledge representation language used and why it was used. For a language like OWL, indicate the OWL profile and expressivity. |
| **Importance:** | MUST |
| **Value:** | OWL version 2, EL profile. |


### E.2 Development environment

|  | Specification |
|---|---|
| **Description:** | The tool(s) used in developing the ontology. |
| **Importance:** | OPTIONAL |
| **Value:** | Protégé, WebProtégé, TawnyOWL, TopBraid Composer, Swoop, etc. |


### E.3 Ontology metrics

|  | Specification |
|---|---|
| **Description:** | Number of classes, properties, axioms and types of axioms, rules and individuals in the ontology. |
| **Importance:** | SHOULD |
| **Value:** | From the Human Phenotype Ontology NAR 2013 article "Human Phenotype Ontology provides a structured, comprehensive and well-defined set of 10,088 classes (terms) describing human phenotypic abnormalities and 13,326 subclass relations between the HPO classes." https://academic.oup.com/nar/article-lookup/doi/10.1093/nar/gkt1026  |


### E.4 Incorporation of other ontologies

|  | Specification |
|---|---|
| **Description:** | The names, versions and citations of external ontologies imported into the ontology and where they are placed in the host ontology. |
| **Importance:** | MUST |
| **Value:** | Import of Uberon core – extended version, 2016-05-11 release under the 'anatomical entity' class. |


### E.5 Entity naming convention

|  | Specification |
|---|---|
| **Description:** | The naming scheme for the entities in the ontology, capturing orthography, organisation rules, acronyms, and so on. |
| **Importance:** | MUST |
| **Value:** | Open Biomedical Ontologies (OBO) Foundry naming conventions; see http://www.obofoundry.org/principles/fp-012-naming-conventions.html. |


### E.6 Identifier generation policy

|  | Specification |
|---|---|
| **Description:** | What is the scheme used for creating identifiers for entities in the ontology. State whether identifiers are semantic-free or meaningful. |
| **Importance:** | MUST |
| **Value:** | Incremental class number, using 10 digit number with ontology name as the prefix. |


### E.7 Entity metadata policy

|  | Specification |
|---|---|
| **Description:** | What metadata for each entity is to be present. This could include, but not be limited to: A natural language definition, editor, edit history, Values, entity label and synonyms, etc. |
| **Importance:** | MUST |
| **Value:** | Each class minimally requires a textual definition, a label, a creator and an edit date. The Ontology for Biomedical  Investigations (OBI) paper <https://www.ncbi.nlm.nih.gov/pubmed/27128319> has a section entitled  "Choice of metadata conventions". |
|


### E.8 Upper ontology

|  | Specification |
|---|---|
| **Description:** | If an upper ontology is used, which one is used and why is it used? If not used, then why. |
| **Importance:** | MUST |
| **Value:** | SUMO, BFO. The Ontology for Biomedical Investigations (OBI) paper <http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0154556> has a sentence "While each had its strengths and weaknesses, BFO was chosen due to its association with the nascent OBO Foundry"  in its discussion. |


### E.9 Ontology relationships

|  | Specification |
|---|---|
| **Description:** | The relationships or properties used in the ontology, which were used and why? Were new relationships required? Why? |
| **Importance:** | MUST |
| **Value:** | The schema.org relationships were imported and used. We used the OBO Relations Ontology. |


### E.10 Axiom patterns 

|  | Specification |
|---|---|
| **Description:** | An axiom pattern is a regular design of axioms or a template for axioms used to represent a category of entities or common aspects of a variety of types of entities. An axiom pattern may comprise both asserted and inferred axioms. The aim of a pattern is to achieve a consistent style of representation. An important family of axiom patterns are Ontology Design pattern (ODP) which are commonly used solutions for issues in representation.  |
| **Importance:** | MUST |
| **Value:** | The axiom patterns described in the Section "The Ontology"  for the Software Ontology in its JBMS paper (http://jbiomedsem.biomedcentral.com/articles/10.1186/2041-1480-5-25). Patterns can be presented as Values or in the form of axiom templates, such as a reference to an ontology design pattern (http://ontologydesignpatterns.org/wiki/Main_Page). |


### E.11 Dereferenceable IRIs 

|  | Specification |
|---|---|
| **Description:** | State whether or not the IRI used are dereferencable to a Web resource. Provide any standard prefix (CURIE). |
| **Importance:** | SHOULD |
| **Value:** | For Value, http://purl.obolibrary.org/obo/GO_0006915 |


## F. Managing Change

### F.1 Sustainability plan 

|  | Specification |
|---|---|
| **Description:** | State whether the ontology will be actively maintained and developed. Describe a plan for how the ontology will be kept up to date. |
| **Importance:** | MUST |
| **Value:** | Outline of sustainability plan, including method to sustain and who will be responsible. |


### F.2 Entity deprecation strategy 

|  | Specification |
|---|---|
| **Description:** | Describe the procedures for managing entities that become removed, split or redefined. |
| **Importance:** | MUST |
| **Value:** | The owl:DeprecatedClass; no class is deleted from the ontology, but deprecated classes are labelled as obsolete with an annotation property. |


### F.3 Versioning policy

|  | Specification |
|---|---|
| **Description:** | State or make reference to the policy that governs when new versions of the ontology are created and released. |
| **Importance:** | MUST |
| **Value:** | The Open Biomedical Ontologies Consortium has a versioning policy, see http://www.obofoundry.org/id-policy.html. This page states "Versions are named by a date in the following format: YYYY-MM-DD. For a given version of an ontology, the ontology should be accessible at the following URL, where <idspace> is replaced by the IDSPACE in lower case." and gives further elaboration. |


## G. Quality Assurance

### G.1 Testing

|  | Specification |
|---|---|
| **Description:** | Description of the procedure used to judge whether the ontology achieves the claims made for the ontology. State, for Value, whether the ontology is logically consistent, answers the queries it claims to answer, and whether it can answer them in a time that is reasonable for the projected use case scenario (benchmarking). |
| **Importance:** | MUST |
| **Value:** | Values of competency questions that can be asked. Values of inferences that can be made. Classification time using an appropriate reasoner: "The ontology was successfully classified by both Pellet 2.3.1 and HermiT 1.3.8 (i.e., is logically consistent) in less than 1 second. All classes in the ontology are satisfiable." |


### G.2 Evaluation

|  | Specification |
|---|---|
| **Description:** | A determination of whether the ontology is of value and significance. An evaluation should show that the motivation is justified and that the objectives of the ontology's development are met effectively and satisfactorily. Describe whether or not the ontology meets its stated requirements, competency questions and goals.  |
| **Importance:** | MUST |
| **Value:** | There is an evaluation described for the Emotion Ontology in the paper "Evaluating the Emotion Ontology through use in the self-reporting of emotional responses in an academic conference". http://jbiomedsem.biomedcentral.com/articles/10.1186/2041-1480-5-38 |


### G.3 Value of use

|  | Specification |
|---|---|
| **Description:** | An illustration of the ontology in use in its an application setting or use case. |
| **Importance:** | MUST |
| **Value:** | to Table S1 in The Ontology for Biomedical Investigations article in PLoS One 2016 https://www.ncbi.nlm.nih.gov/pubmed/27128319 shows the projects using OBI. |


### G.4 Institutional endorsement

|  | Specification |
|---|---|
| **Description:** | State whether the ontology is endorsed by the W3C, the OBO foundry or some organisation representing a community. |
| **Importance:** | OPTIONAL |
| **Value:** | SNOMED is mandated for use by many national health organisations. The Chemicals of Biological Interest Ontology is a member of the OBO Foundry.   |



### G.5 Evidence of use

|  | Specification |
|---|---|
| **Description:** | An illustration of active projects and applications that use the ontology.   |
| **Importance:** | MUST |
| **Value:** | The Gene Ontology is used to annotate the gene products for their molecular function, biological process and cellular component in many species specific and cross-species databases. |


