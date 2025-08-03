# How RAG Was Used in This Project

This project uses Retrieval-Augmented Generation (RAG) to generate structured academic profiles based on faculty CVs.

## Steps:
1. Faculty CV is uploaded and indexed in IBM Watsonx Vector Index.
2. The system retrieves relevant document chunks based on user queries.
3. IBM Granite LLM uses those chunks to generate accurate answers or profile sections.
4. Outputs are grounded in actual document content — enabling trustworthy AI.

## Example Queries:
- "List academic qualifications"
- "Generate profile based on uploaded CV"
- "Summarize FDPs, patents, and achievements"
