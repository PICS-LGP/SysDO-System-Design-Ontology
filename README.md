# SDO-System-Design-Ontology

The **System Design Ontology (SDO)** is a domain-level ontology developed within the **EXCELAB** project to support model interoperability across system engineering tools in industrial contexts.

## Project Context: EXCELAB

This work is carried out as part of the **EXCELAB** project, funded by the Civil Aviation Research Council (CORAC) under the French Civil Aviation Authority (DGAC). It aims to facilitate co-development of aircraft products and their associated production systems through semantic-driven interoperability.

> The authors thank **Airbus**, **Dassault Aviation**, **Daher Aerospace**, **Airbus Atlantic**, and **Liebherr Aerospace Toulouse** for their collaboration and support.

## Objectives

- Enable semantic interoperability between tools like **Cameo**.
- Provide a **semantic hub** using SDO to translate, map, and validate model elements.
- Support both **automated** and **manual** data exchange via APIs and knowledge graphs.
- Improve traceability and adaptability across evolving models and ontologies.

## Use Case

A concrete use case involves **Airbus** simulating the co-development of a small aircraft and its production system, focusing on  **global manufacturing** and **wing manufacturing**.

## Repository Content

- `/CQ and Queries`: Competency questions and corresponding returns
- `SystemDesignOnto_v6.rdf`: The main ontology file

## Tools Involved

- Java (for OWL-API/Jena)
- Cameo (for original design model development)
- Protégé (for ontology editing)

