Problem Statement 
IT support requests often arrive as incomplete, unstructured descriptions, making classification, prioritization, duplicate detection, knowledge retrieval, and routing inconsistent. Helpdesk teams need an assistant that asks only necessary follow-up questions, remembers relevant context, recommends approved guidance with sources, explains priority and ownership, and prepares reviewable tickets without bypassing human approval.

Solution Approach
Collect issue details through guided prompts, dropdown tags, asset lookup, and session memory.
Retrieve approved local articles, cite sources, detect recent duplicates, and incorporate resolution feedback.
Calculate explainable priority from impact and urgency, then map categories to resolver groups.
Generate editable JSON tickets, flag uncertain cases, and require human review before routing.


GenAI Concepts Used
Use large language models to extract structured incident fields while preserving user-provided context.
Apply retrieval-augmented generation over approved support articles, returning grounded recommendations with citations.
Combine deterministic classification and priority rules with confidence thresholds and similarity-based duplicate detection.
Maintain session memory, use tool-assisted asset lookup, capture feedback, and audit human decisions.
