# Defence & Aerospace RAG Sample Dataset

Synthetic, non-operational sample documents for demonstrating a RAG/LangGraph pipeline.

Folders:
- manuals/       Maintenance manuals
- bulletins/     Technical bulletins
- reports/       Maintenance and analytics reports

Suggested ingestion metadata:
document_id, document_type, title, revision, effective_date, aircraft, system,
classification, source_file, section, page_number (if later converted to PDF).

Suggested test queries:
1. What is the hydraulic leakage inspection procedure?
2. Which document contains the latest hydraulic inspection procedure?
3. What does bulletin TB-HYD-2026-001 recommend?
4. How many hydraulic incidents occurred in 2026?
5. Which documents are related to hydraulic leakage?
6. What is the current hydraulic manual revision?
7. Compare the hydraulic bulletin with the maintenance manual.
8. Find avionics connector-related maintenance information.

All content is fictional and should not be used for real maintenance, engineering,
safety, defence, or aerospace operations.
