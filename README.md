# Sat-KG-Pipeline
AI-powered Knowledge Graph Pipeline for Satellite Power Systems Fault Diagnosis 2025 · Developed a customized pipeline that translates basic human troubleshooting inputs into a structured knowledge graph, helping satellite engineers quickly identify faults.

This project implements an intelligent pipeline that transforms natural language troubleshooting inputs into a structured Knowledge Graph (KG) to assist satellite engineers in diagnosing faults in power systems.

By integrating AI language models (e.g., MistralAI) and semantic technologies (RDF, SPARQL), this system enables automated fault reasoning by mapping ambiguous or high-level descriptions into machine-readable fault scenarios.

Features
NLP-driven fault understanding
Uses co-reference resolution, tokenization, and chunk-based processing to extract key information from user inputs.
Knowledge Graph Construction
Converts insights into RDF triples and stores them in a SPARQL-compatible triplestore for efficient querying.
Real-time Information Augmentation
Leverages SerpAPI and OCR to enrich context from technical documents and online sources.
Designed for Satellite Power Systems
Tailored to handle diagnostic patterns and failure modes relevant to satellite electrical subsystems.
Tech Stack
Languages & Tools: Python, RDF, SPARQL
Libraries & APIs: MistralAI, SerpAPI, OCR (Tesseract), spaCy
Techniques: Co-reference Resolution, NLP Tokenization, Chunking, Semantic Graph Generation
