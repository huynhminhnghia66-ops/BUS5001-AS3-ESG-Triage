# Q4 NotebookLM Experiment Log
## BUS5001 Assessment 3 — Evaluating NotebookLM

**Date:** June 2026  
**Notebook name:** BUS5001-AS3-Q4-ESG-Research  
**Sources uploaded:** 3  

---

## Sources Used

| # | File | Type | Description |
|---|---|---|---|
| 1 | AI-Driven-Sustainability-Automation.pdf | PDF | Academic paper on AI and ESG automation |
| 2 | AS3_Q2_CloudSecurity.docx | Word | BUS5001 Q2 report on Toyota cloud breach |
| 3 | Assessment_3_Details_and_instructions.docx | Word | BUS5001 Assessment 3 brief |

---

## Feature 1: Chat / Q&A with Sources

**Query asked:**
> "What are the main cloud security vulnerabilities identified in the Toyota data breach, and what prevention measures are recommended?"

**Result summary:**
NotebookLM correctly identified both failure points from the Q2 source document: hardcoded credentials in a public GitHub repository and a passwordless cloud database left exposed for nearly a decade. The response was well-structured with numbered prevention steps and cited specific source footnotes for each claim. All five prevention measures (secrets detection, CSPM, zero-trust IAM, Azure Policy, third-party audits) were accurately reproduced from the source document with correct attribution.

**Accuracy:** High — all claims traced directly to uploaded sources  
**Usefulness:** High — saved significant time compared to manual document review  

---

## Feature 2: Audio Overview

**Settings used:** Deep Dive (2 AI hosts), English, Default length  
**Output duration:** 19 minutes 21 seconds  

**Result summary:**
NotebookLM generated a podcast-style conversation between two AI hosts discussing the key themes across all three source documents. The discussion covered AI-cloud synergy for ESG reporting, the Toyota security breach as a case study, and practical prevention measures. The audio was coherent and well-paced, connecting ideas across sources in a way that would be useful for revision or for someone who prefers audio learning.

**Accuracy:** Moderate to High — content was faithful to sources but occasionally simplified complex technical points  
**Usefulness:** High for review and accessibility; the 19-minute runtime makes it practical for commute listening  

---

## Feature 3: Study Guide (Quiz)

**Output:** 12 multiple-choice questions titled "Sustainability Quiz"  

**Sample question generated:**
> "How does the synergy between Cloud Computing and Artificial Intelligence address the issue of 'data silos' in Environmental, Social, and Governance (ESG) reporting?"

**Result summary:**
NotebookLM generated 12 questions covering concepts from all three source documents, including ESG reporting frameworks, cloud security principles, and AI-driven sustainability automation. Questions were well-formed and at an appropriate academic level. The quiz format is directly useful for exam preparation and self-assessment.

**Accuracy:** High — questions were grounded in source content  
**Usefulness:** High for self-testing and identifying knowledge gaps  

---

## Feature 4: Mind Map (Beta)

**Output:** Visual mind map titled "AI-Cloud Synergy for ESG & Security"

**Key branches generated:**
- The Foundation (AI-Cloud Synergy)
- ESG Reporting Automation (Smart Data Ingestion, Automated Framework Mapping, Audit-Ready Assurance)
- Green Operations Optimization (Predictive Energy Management, Smart Supply Chains, Proactive Asset Maintenance)
- Security Prevention Measures — Lessons from Toyota (Automated Secrets Detection, CSPM, Zero-Trust IAM, Azure Policy, Third-Party Audits)

**Result summary:**
The mind map successfully synthesized concepts from all three sources into a single coherent visual structure. Notably, it connected the Toyota breach lessons directly to the broader ESG-cloud theme, which reflects genuine cross-document synthesis rather than simple summarization of individual files.

**Accuracy:** High — all nodes traced to source content  
**Usefulness:** High for visual learners and for identifying conceptual relationships across documents  

---

## Overall Observations

| Feature | Accuracy | Usefulness | Notes |
|---|---|---|---|
| Chat/Q&A | High | High | Best for targeted questions; citations provided |
| Audio Overview | Moderate-High | High | Useful for revision; simplifies some technical content |
| Study Guide | High | High | Good for self-assessment; 12 well-formed questions |
| Mind Map | High | High | Strong cross-document synthesis; Beta feature |

**Key limitation observed:** NotebookLM's responses are bounded entirely by the uploaded sources. When asked about topics not covered in the documents, it correctly declines to speculate, which is both a strength (accuracy) and a limitation (scope).
