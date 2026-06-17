# BoloArtKG

## Enriching ARCO with Knowledge Graphs and Artificial Intelligence

### Project Overview

BoloArtKG is a digital humanities project developed to represent the artistic heritage of Bologna through Knowledge Graph technologies. The project explores the relationships between artists, artworks, and the Bolognese School, providing a structured representation of cultural heritage knowledge.

Cultural heritage institutions increasingly rely on digital technologies to preserve, organize, and disseminate information about artworks, artists, and historical monuments. Among these technologies, Knowledge Graphs and Artificial Intelligence have become essential tools for managing large volumes of cultural heritage data and revealing meaningful relationships between cultural entities.

### Introcution
This project focuses on the Bolognese School of Painting, one of the most influential artistic movements in Italy and Europe. Using ARCO, the Italian Knowledge Graph for Cultural Heritage, the project investigates how semantic technologies can be employed to retrieve, organize, and enrich information related to painters, artworks, museums, and cultural institutions associated with Bologna.

The project combines Cultural Heritage studies, Semantic Web technologies, Knowledge Graphs, and Artificial Intelligence. Through SPARQL queries, information is extracted from ARCO and organized into a semantic structure. Artificial Intelligence is then used to identify gaps in the available data and propose additional relationships and semantic descriptions. The project demonstrates how Knowledge Graphs and AI can contribute to a richer representation of cultural heritage information.
<img width="7444" height="260" alt="image" src="https://github.com/user-attachments/assets/569780d7-7ce6-4d03-ba0a-3b9eaa3d3890" />

### Research Questions
The project is guided by the following research questions:

RQ1: What is the Bolognese School of Painting?
RQ2: Which cultural heritage resources in ARCO are associated with Bologna?
RQ3: Who are the principal artists related to the Bolognese School?
RQ4: What gaps can be identified in ARCO regarding the representation of the Bolognese School?
RQ5: How can Artificial Intelligence contribute to the enrichment of cultural heritage data?
<img width="1504" height="565" alt="image" src="https://github.com/user-attachments/assets/dfaf3d9a-f3f2-4bb7-a35b-6a804294ced9" />

### Project Objectives

- Model cultural heritage entities
- Represent semantic relationships
- Visualize artist-artwork connections
- Demonstrate Knowledge Graph principles
- Support cultural heritage exploration

### Theoretical Background
Cultural Heritage and Linked Open Data
The digitization of cultural heritage has transformed the way cultural institutions manage and share information. Linked Open Data enables cultural heritage resources to be connected through semantic relationships, facilitating interoperability between datasets and improving access to information.

ARCO Knowledge Graph
ARCO is the Italian Knowledge Graph for Cultural Heritage developed to publish cultural heritage information as Linked Open Data. It contains structured information concerning artworks, archaeological objects, museums, monuments, and cultural institutions.
ARCO is based on Semantic Web standards and allows users to access cultural heritage information through SPARQL queries.
<img width="4496" height="403" alt="image" src="https://github.com/user-attachments/assets/91c71555-cee1-444e-8e50-3907304dac6a" />

Semantic Web Technologies
The Semantic Web is based on technologies such as RDF, OWL, and SPARQL.
RDF represents knowledge through triples composed of a subject, predicate, and object.
OWL allows the formal description of concepts and relationships.
SPARQL enables users to retrieve and analyze information stored in Knowledge Graphs.
These technologies facilitate machine-readable representations of cultural heritage information.

Artificial Intelligence and Cultural Heritage
Artificial Intelligence has increasingly been applied in the cultural heritage domain. AI techniques can support entity recognition, relationship discovery, semantic enrichment, automatic summarization, and knowledge extraction.
By combining Knowledge Graphs and AI, it becomes possible to identify hidden relationships and generate additional semantic information that may not be explicitly represented in existing datasets.
<img width="3488" height="660" alt="image" src="https://github.com/user-attachments/assets/432a0232-1c91-4897-8744-d219f86f3c29" />

### The Bolognese School of Painting
The Bolognese School of Painting emerged in Bologna during the late sixteenth century and became one of the most influential artistic movements in Europe.
The movement developed as a reaction against Mannerism and promoted a balance between natural observation and classical artistic ideals. It played a crucial role in the development of Baroque painting and influenced generations of artists throughout Europe.
Important representatives of the Bolognese School include:
		-Annibale Carracci
		-Agostino Carracci
		-Ludovico Carracci
		-Guido Reni
		-Guercino
		-Domenichino
Their works continue to be preserved in museums, churches, galleries, and cultural institutions both in Italy and abroad.
<img width="3991" height="687" alt="image" src="https://github.com/user-attachments/assets/3025a818-0a13-4262-a661-7b3029b4047f" />

### Main Entities

- Bologna
- Bolognese School
- Carracci Family
- Artists
- Artworks

### Featured Artists

- Annibale Carracci
- Agostino Carracci
- Ludovico Carracci
- Guido Reni
- Guercino

### Methodology
The project follows four main stages.

Data Collection
Data were collected through the ARCO SPARQL Endpoint. Queries were designed to retrieve information related to Bologna, paintings, artists, and museums.

Knowledge Extraction
The retrieved information was analyzed to identify key entities such as:
Artists
Artworks
Museums
Places
Artistic movements
<img width="2443" height="702" alt="image" src="https://github.com/user-attachments/assets/2fbf2b19-3c8a-4aba-b43c-44daf55344fe" />

Knowledge Graph Construction
The identified entities were connected through semantic relationships.
Examples include:
Artist → created → Artwork
Artwork → located in → Museum
Artist → associated with → Bologna

AI-Based Enrichment
Artificial Intelligence was employed to enrich the extracted information by:
Identifying entities
Discovering implicit relationships
Generating semantic descriptions
Suggesting additional RDF triples
<img width="1160" height="904" alt="image" src="https://github.com/user-attachments/assets/ecc94ace-71a1-4dd9-8798-72d05b94e777" />

### Technologies Used

- Google Sites
- GitHub
- Knowledge Graph Modelling
- SPARQL
- Cultural Heritage Data

### SPARQL Queries and Results
Several SPARQL queries were executed through the ARCO endpoint to retrieve information related to the Bolognese School of Painting.
The results revealed cultural entities associated with Bologna, including artists, institutions, and heritage resources.
The retrieved data provided the basis for constructing the Knowledge Graph and identifying potential gaps in the representation of artistic relationships.
<img width="2344" height="215" alt="image" src="https://github.com/user-attachments/assets/98d776b6-352d-44cb-83d0-fa3c35fff656" />

### AI Enrichment
The analysis revealed that some artistic relationships are not explicitly represented in ARCO.
For example, although artists such as Guido Reni and Annibale Carracci are associated with Bologna, their membership in the Bolognese School may not always be explicitly represented through semantic relationships.
Artificial Intelligence was therefore used to propose additional semantic triples.
Examples:
Guido Reni → belongsTo → Bolognese School
Annibale Carracci → belongsTo → Bolognese School
Guercino → influencedBy → Carracci School
These enrichments improve the semantic representation of cultural heritage knowledge.
<img width="3351" height="395" alt="image" src="https://github.com/user-attachments/assets/6310219f-cd49-48d0-8b1e-cd4ede0f92b9" />

### Results and Discussions
The project demonstrates several important findings.
First, ARCO provides a rich repository of cultural heritage information that can be explored through Semantic Web technologies.
Second, SPARQL queries enable the retrieval of structured information concerning artists, artworks, and cultural institutions.
Third, Knowledge Graphs facilitate the organization and visualization of relationships among cultural entities.
Finally, Artificial Intelligence can contribute to knowledge enrichment by identifying missing relationships and generating semantic descriptions.
The combination of ARCO, Knowledge Graphs, and AI therefore offers significant opportunities for enhancing access to cultural heritage information.
<img width="2308" height="417" alt="image" src="https://github.com/user-attachments/assets/78a8bd80-b82d-422f-b97a-e76293f1aada" />

### Limitations/Gaps
Gaps
Several limitations were identified during the project.
ARCO does not explicitly represent all artistic schools.
Some relationships must be inferred rather than directly retrieved.
Metadata completeness varies across cultural entities.
AI-generated enrichments require expert validation.

Future Work
Future developments may include:
Integration with Wikidata and Europeana.
Expansion of the Knowledge Graph to additional artistic schools.
Development of interactive visualizations.
Implementation of Retrieval-Augmented Generation systems.
Automatic generation of semantic annotations for artworks.
<img width="1081" height="971" alt="image" src="https://github.com/user-attachments/assets/b37dd209-96ad-49fa-914b-8847c05c3b3c" />

### Conclusion
This project demonstrates how Knowledge Graphs and Artificial Intelligence can contribute to the enrichment of cultural heritage information.
Using the Bolognese School of Painting as a case study, the project showed how ARCO can be queried through SPARQL, how semantic relationships can be represented in a Knowledge Graph, and how AI can be used to identify and enrich missing knowledge.
The integration of ARCO, Semantic Web technologies, Knowledge Graphs, and Artificial Intelligence represents a promising approach for supporting research, education, and public access within the field of Digital Humanities.
<img width="3941" height="260" alt="image" src="https://github.com/user-attachments/assets/0ab2c840-fb83-4392-87c1-7aca1d60fdab" />

### References
ARCO – Italian Knowledge Graph for Cultural Heritage.
ARCO SPARQL Endpoint.
Berners-Lee, T., Hendler, J., & Lassila, O. (2001). The Semantic Web. Scientific American.
Bizer, C., Heath, T., & Berners-Lee, T. (2009). Linked Data: The Story So Far. International Journal on Semantic Web and Information Systems.
University of Bologna Course Materials – Knowledge Computing for the Humanities.
<img width="2184" height="440" alt="image" src="https://github.com/user-attachments/assets/226b4730-3015-4eeb-b4a9-b48987f7d703" />

### Author

Jean Paul Ngouffo Nkouedjo and Henri Lamine Faye

University of Bologna
School of Languages, Literatures, Translation and Interpreting
Department of Modern Languages, Literaturess and Cultures
Programme in Language, Society and Communication
<img width="1256" height="176" alt="image" src="https://github.com/user-attachments/assets/35a69940-94e5-43d4-84c1-2e5732cbc45e" />



