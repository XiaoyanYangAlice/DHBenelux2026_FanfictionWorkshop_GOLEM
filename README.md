# DHBenelux 2026 – GOLEM Workshop: Fanfiction Character Analysis with Knowledge Graphs

This repository contains the workshop materials presented at **DHBenelux 2026**, focused on hands-on characterization analysis using the **GOLEM ontology** and its associated knowledge graph of fanfiction data. The workshop introduces participants to semantic modeling of fictional characters and narrative events, and guides them through SPARQL-based querying of a real fanfiction knowledge graph.

---

## 📁 Repository Contents

### 1. `DHBenelux2026-GOLEM.pptx` — Presentation Slides
The slide deck accompanying the workshop. It provides an overview of the GOLEM project, the theoretical background of ontology-based character modeling, and a roadmap for the practical session.

### 2. `DHBenelux_2026_GOLEM.ipynb` — Tutorial Notebook
An interactive Jupyter/Google Colab notebook with **10 SPARQL competency queries** (CQ1–CQ10) organized in two parts:

**Part 1 – Fanfiction Metadata Exploration**
- Basic work metadata (titles, creators)
- Metrics and tags (kudos, hits, content warnings)
- Publication year distribution
- Popular fanfiction filtering
- Tag and romantic category analysis

**Part 2 – Character Modeling and Analysis**
- Character appearance across fanfiction works
- Character death analysis (victims, perpetrators)
- Romantic relationships of deceased characters
- Gender distribution of victims
- Most frequently killed characters
- Biographical, physical, and psychological character features
- Cause-of-death comparison: canon vs. fanfiction

The notebook connects to the live GOLEM SPARQL endpoint and can be run directly in Google Colab.

### 3. `DHBenelux2026_Fanfiction_Workshop_GOLEM_Ontology_Reading.docx` — Ontology Reference Sheet
A handout listing the ontology classes, properties, and namespace prefixes used in the practical session. Covers:
- Fanfiction metadata core classes (CIDOC-CRM, LRMoo, Schema.org)
- Character core classes (`gc:G0_Character-Stoff`, `gc:G1_Character`, `gc:G4_Social_Relationship`, etc.)
- Object and data properties with domain/range descriptions and worked examples

---

## 🔗 Related Resources

| Resource | Description | Link |
|---|---|---|
| **GOLEM Ontology** | Full documentation of the GOLEM ontology (classes, properties, modules) | [golem-ontology/wiki](https://github.com/GOLEM-lab/golem-ontology/wiki) |
| **GOLEM Ontology Portal** | Interactive ontology browser | [ontology.golemlab.eu](https://ontology.golemlab.eu/) |
| **Character Module Paper** | Repository for the Character Ontology module and accompanying paper | [Character_Ontology_Paper](https://github.com/GOLEM-lab/Character_Ontology_Paper/tree/main) |
| **GOLEM Data Endpoint** | SPARQL endpoint used in the notebook queries | [data.golemlab.eu](https://data.golemlab.eu) |

---

## 🚀 Getting Started

The tutorial notebook is designed to run in **Google Colab** with no local setup required:

1. Open `DHBenelux_2026_GOLEM.ipynb` in Google Colab (or Jupyter).
2. Run the SPARQL setup cell to install the required `SPARQLWrapper` library.
3. Work through Part 1 (metadata queries) and Part 2 (character analysis queries) in order.
4. Use the ontology reference sheet (`*.docx`) to look up classes and properties as needed.

---

## 📚 Background

**GOLEM** (Graph-based Ontology for Literary and Epistemological Modeling) is a knowledge graph and ontology framework for the semantic representation of literary and fictional characters, narrative events, and their relationships. It builds on established standards including:

- [CIDOC-CRM](http://www.cidoc-crm.org/) — cultural heritage modeling
- [LRMoo](https://www.ifla.org/publications/node/11231) — bibliographic/work modeling (IFLA LRM in OWL)
- [Schema.org](https://schema.org/) — web-oriented metadata

The workshop corpus focuses on fanfiction from **Archive of Our Own (AO3)**, using the Orpheus myth as a case study to trace how canonical characters are reinterpreted across fan-authored works.

---

## 📄 Citation

If you use these materials, please cite the DHBenelux 2026 workshop presentation and the GOLEM project accordingly. For the ontology itself, refer to the documentation at [github.com/GOLEM-lab/golem-ontology/wiki](https://github.com/GOLEM-lab/golem-ontology/wiki).

---

## 🪪 License

Please refer to the GOLEM project for licensing terms of the ontology and data. Workshop materials in this repository are shared for educational purposes.
