# Smart Procurement Navigator

> Version: 2.0.0
> Current Objective: Achieve a full-chain closed loop covering "Upload Procurement Documents / Technical Specifications -> Build Evaluation Model -> Output Response Proposal Architecture -> Produce Chapter Drafts -> Complete Compliance Review".

## 1. System Positioning

Smart Procurement Navigator is an intelligent procurement collaboration system for marketing, commercial, proposal, bid preparation, and business decision-making teams. It spans the complete business chain from opportunity assessment, evaluation modeling, response architecture design, chapter writing, to pre-submission quality assurance, adapting to various procurement and bidding projects under the framework of the *Government Procurement Law of the People's Republic of China* and the *Bidding and Tendering Law of the People's Republic of China*.

| Capability Module | Objective |
| --- | --- |
| Opportunity Identification | Receive procurement announcements or information sources, output opportunity summaries and key deadline alerts |
| Bid Feasibility Assessment | Evaluate qualification conditions, track record, budget, delivery capability, and competitive risks |
| Procurement Document Interpretation | Extract qualification thresholds, evaluation methods, submission specifications, and disqualification clauses |
| Material Structuring | Convert procurement documents, technical specifications, reference files, and knowledge bases into searchable text |
| Evaluation Model Construction | Distinguish disqualification clauses, scoring items, objective scoring materials, and response chapter mapping |
| Bid Task Decomposition | Output material checklists, responsible persons, deadlines, and collaboration nodes |
| Response Proposal Architecture Design | Output pre-index tables, full chapter outlines, chapter anchors, and page planning |
| Response Draft Generation | Produce chapter drafts based on evaluation items, technical specifications, and knowledge bases |
| Draft Polishing and Visual Enhancement | Remove templated expressions and internal strategy terms, and output chart placeholder indexes |
| Compliance Review | Check for missing items, formatting, deviations, key data, reference residuals, and disqualification risks |
| Final Submission Review | Final consistency verification and seal/signature check before submission |
| Experience Accumulation and Knowledge Reuse | Extract root causes of winning/losing bids, and accumulate reusable materials and strategies |

## 2. File Structure

```text
smart-procurement-navigator/
  README.md
  agent.yaml
  system_prompt.md
  workflows.md
  runbook.md
  skills/
    procurement_skills.yaml
  knowledge/
    README.md
  templates/
    opportunity_brief.md
    tender_analysis_report.md
    score_model.md
    response_outline.md
    service_scheme_structure.md
    review_report.md
    consistency_check_report.md
  test_cases/
    p0_demo_cases.md
  demo/
    demo_script.md
```

## 3. Core Closed Loop

```text
User uploads procurement announcement or procurement documents
  -> Identify basic project information
  -> Extract qualification thresholds and evaluation criteria
  -> Build evaluation scoring model and no-deviation index
  -> Output bid task checklist
  -> Output complete response proposal chapter structure and chapter drafts
  -> Output draft polishing and compliance review opinions
  -> Output pre-submission final review clearance checklist
```

## 4. Key Boundaries

- This system can produce analysis reports, checklists, outlines, drafts, and review opinions.
- This system cannot replace the bid decision-maker in making final bidding decisions.
- Quotations, commitments, seals/signatures, qualification authenticity verification, and final response documents must be confirmed by a human.
- When involving customer names, amounts, qualifications, and past performance, display and archive must follow permission rules.
- Internal evaluation strategy expressions, exaggerated wording, and reference project residuals must not be retained in formal response documents.
- Comply with the provisions on fair competition and information disclosure in the *Government Procurement Law of the People's Republic of China*.


## v2.0.0 New Additions (2026-06-16)

### Legal and Regulatory Framework
- *Bidding and Tendering Law of the People's Republic of China* and its Implementation Regulations
- *Government Procurement Law of the People's Republic of China* and its Implementation Regulations
- 2024 State Council Document No. 21: *Opinions on Innovating and Improving Institutional Mechanisms to Promote Standardized and Healthy Development of the Bidding and Tendering Market*
- 2025 New Regulations on Remote Cross-Location Evaluation

### Full Process — 7 Major Stages Explained
Tendering → Bidding → Bid Opening → Bid Evaluation → Award Decision → Contract Signing → Contract Performance

### Bid Evaluation Method System
- Three approaches under the Comprehensive Scoring Method (Fixed Score Method, Interval Scoring Method, Rank-Based Scoring Method)
- Compliance analysis
- Abnormal price score identification and response strategies

### Electronic Bidding Platform Adaptation
- Remote cross-location evaluation: primary/secondary venue mechanism
- Electronic seal/signature CA mutual recognition
- Remote cross-location evaluation expert selection rules

### In-Depth Guide to Bid Document Preparation
- Commercial bid / Technical bid / Price bid volume preparation specifications
- Common bid rejection causes and avoidance strategies (30+)

### Remedy Mechanisms
- Three-tier challenge/complaint/appeal system (7→15→60 day time limits)
- SME preferential policies
- Consortium bidding specifications
- Prequalification vs Post-qualification
- Double envelope process
- 20+ key deadline summary