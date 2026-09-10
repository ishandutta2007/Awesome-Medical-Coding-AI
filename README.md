# Awesome-Medical-Coding-AI

## Top Medical Coding AI



**Curated List of Medical Coding AI Platforms, Autonomous Coding Systems & Open-Source Medical Coding Software**

*Focused on AI-assisted medical coding, ICD-10-CM, ICD-10-PCS, CPT, HCPCS, clinical NLP, computer-assisted coding (CAC), autonomous coding, coding QA, revenue-cycle automation, documentation intelligence, and open-source medical coding infrastructure*

**Last updated: September 2026**



This repository tracks notable **SaaS/Hosted Medical Coding AI platforms** and **Open-Source Medical Coding / Clinical NLP projects**.



Medical Coding AI sits at the intersection of **clinical NLP, medical terminology, computer-assisted coding, revenue-cycle management, clinical documentation, EHR integration, and AI reasoning**.



Modern systems increasingly attempt to move beyond simple code lookup toward:



* Clinical documentation understanding

* Diagnosis and procedure extraction

* ICD-10-CM prediction

* ICD-10-PCS prediction

* CPT / HCPCS coding

* HCC / risk-adjustment coding

* DRG optimization

* Coding validation

* Documentation improvement

* Coding QA

* Autonomous coding

* Human-in-the-loop review

* Revenue-cycle automation



**Open-source emphasis:** This list intentionally gives substantial coverage to open-source medical coding projects, clinical NLP frameworks, ICD-10 auto-coders, medical language models, terminology systems, and research implementations.



> **Important distinction:** A clinical NLP library, pretrained medical LLM, or ICD-10 dataset is not necessarily a complete medical coding platform. The Open-Source section therefore distinguishes **complete coding systems** from **building blocks** that can be combined into one.



## Table of Contents



* [SaaS/Hosted Platforms](#saashosted-platforms)

* [Open-Source](#open-source)

* [Open-Source Medical Coding Systems](#open-source-medical-coding-systems)

* [Open-Source Clinical NLP](#open-source-clinical-nlp)

* [Medical Language Models](#medical-language-models)

* [Medical Terminology & Coding Infrastructure](#medical-terminology--coding-infrastructure)

* [Research & Auto-Coding Projects](#research--auto-coding-projects)

* [Coding Architecture](#coding-architecture)

* [Medical Coding AI Capability Matrix](#medical-coding-ai-capability-matrix)

* [SaaS vs Open Source](#saas-vs-open-source)

* [Recommended Open-Source Shortlist](#recommended-open-source-shortlist)

* [Open-Source Medical Coding Stack](#open-source-medical-coding-stack)

* [Open-Source Opportunities](#open-source-opportunities)

* [How to Contribute](#how-to-contribute)

* [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



### Leading Medical Coding AI Platforms

| Platform | Description & Core Focus | Pricing (Starting Tier) | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **CodaMetrix** | AI-powered autonomous medical coding platform automating professional & facility coding workflows across multi-specialty health systems. | Starts at **$0.75 – $2.50 per coded encounter** (transactional fee; enterprise agreements baseline ~$150,000/year). | **60-day structured pilot program** for qualified health systems (limited to single department evaluation dataset, no perpetual free tier). |
| **Fathom** | Deep-learning autonomous medical coding engine automating ICD-10, CPT, and HCPCS coding from unstructured clinical documentation across ED, ambulatory, and radiology. | Starts at **$1.10 – $2.25 per processed chart** (or 30%–50% cost-reduction performance pricing; enterprise baseline ~$10,000/month). | **30-day historical chart audit & ROI analysis trial** (evaluates up to 10,000–50,000 retrospective encounters, no perpetual free tier). |
| **Nym** | Computational linguistics engine transforming clinical documentation into standardized codes autonomously with zero human intervention for supported charts. | Starts at **$1.20 – $2.80 per auto-coded chart** (transactional billing model; enterprise contract minimum ~$12,500/month). | **60-day single-specialty pilot program** (evaluates retrospective chart cohort with benchmark accuracy report, no perpetual free tier). |
| **AKASA** | Unified AI revenue-cycle platform utilizing generative AI and machine learning for automated coding, denial management, and prior authorization workflows. | Starts at **$0.85 – $1.75 per claim transaction** or **4% – 8% of recovered value** (outcome-based fee model; enterprise baseline ~$15,000/month). | **30-day risk-free workflow audit & evaluation pilot** (limited to initial department revenue-cycle analysis, no perpetual free tier). |
| **3M M*Modal** | Clinical documentation, ambient AI, and speech-driven computer-assisted coding (part of Solventum portfolio). | Starts at **$79 – $99/user/month** for speech/dictation tools; comprehensive CAC modules start at **$150 – $280/provider/month**. | **14-day evaluation demo/pilot** for clinical practices (limited to 1–5 provider test licenses, no perpetual free tier). |
| **Omega Healthcare** | Tech-enabled revenue cycle services combining AI automation with human-in-the-loop medical coding, CDI, and billing operations. | Starts at **$18 – $26/hour per dedicated coder** or **$1.50 – $3.50 per coded chart** (or 4%–8% of net collections). | **30-day diagnostic coding sample audit** (limited to review of 200–500 sample claims, no perpetual free tier). |
| **CorroHealth** | Healthcare RCM organization providing autonomous coding (REVANT), CDI, auditing, and utilization management. | Starts at **$1.25 – $2.75 per automated encounter** (or 4.5%–7.5% of net collections; enterprise annual base from ~$20,000/year). | **30-day baseline coding accuracy audit** (limited to 500 sample charts, no perpetual free tier). |
| **Claimable** | AI-powered medical coding validation, denial management, and appeal generation platform. | Starts at **$79.00/month** (portal subscription) or **$39.95 per individual appeal claim**. | **30-day free trial** (limited to 5 appeal simulations and basic claim denial checks, no perpetual free tier). |
| **Clinithink** | Clinical NLP platform (CLiX) converting unstructured clinical narrative into structured SNOMED CT and ICD terminology for coding and CDI. | Starts at **$3,500/month** (or **$0.05 – $0.15 per unstructured note** processed in batch; enterprise tier from ~$45,000/year). | **14-day sandbox access** (limited to 1,000 API/document test processing calls, no perpetual free tier). |
| **Waystar AI Coding** | Cloud-based revenue cycle and AI coding suite integrated into payments clearinghouse and claims workflows. | Starts at **$0.25 – $0.65 per claim transaction** (plus platform base fee starting at **$150 – $300/month** per practice). | **30-day onboarding pilot** (limited to clearinghouse test batch up to 250 test claims, no perpetual free tier). |

### Additional Medical Coding / CAC Platforms

| Platform | Description & Core Focus | Pricing (Starting Tier) | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **Optum Encoder / Optum CAC** | Comprehensive encoder and computer-assisted coding ecosystem offering ICD-10, CPT, HCPCS code lookup, LCD/NCD rules, and compliance tools. | Starts at **$299.95/user/year** ($24.99/month equivalent) for Standard Online; Expert Online at **$999.95/user/year**; enterprise CAC from ~$15,000/year. | **30-day free trial** for EncoderPro Online (full access to code search, crosswalks, and regulatory updates; 1 user license limit). |
| **3M 360 Encompass** | Enterprise computer-assisted coding (CAC), clinical documentation integrity (CDI), and inpatient/outpatient DRG grouping platform (Solventum). | Starts at **$1,500 – $3,500 per hospital bed/year** (or enterprise institutional contract starting at ~$50,000/year). | **30-day structured on-site/virtual pilot evaluation** (limited to test hospital environment, no perpetual free tier). |
| **Dolbey (Fusion CAC / Fusion Narrate)** | Computer-assisted coding and cloud speech recognition platform providing automated chart scoring, CDI, and transcription. | Starts at **$45 – $79/user/month** for Fusion Narrate; Fusion CAC enterprise modules start at **~$12,000/year**. | **14-day free trial** for Fusion Narrate speech recognition (full dictation & EHR integration features; 1 provider license limit). |
| **MModal Fluency Direct / Fluency for Coding** | Real-time speech recognition, documentation intelligence, and automated CAC suggestions integrated with EHRs. | Starts at **$99/user/month** (annual contract) or CAC engine add-on starting at **~$800/month**. | **14-day clinical trial license** (limited to 1 provider profile with standard medical vocabularies, no perpetual free tier). |
| **Nuance / Microsoft Cloud for Healthcare** | Ambient clinical AI (DAX Copilot) and cloud speech recognition (Dragon Medical One) with downstream clinical coding intelligence. | Starts at **$79 – $99/user/month** for Dragon Medical One (+ ~$525 one-time setup); DAX Copilot starting at **$369 – $600/provider/month**. | **7-day to 30-day free trial** through authorized Microsoft/Nuance partners (full voice dictation feature access; 1 provider license limit). |
| **CPSI / TruCode (TruBridge)** | Encoder software and terminology infrastructure for hospitals and health systems, supporting ICD-10, CPT, and HCPCS workflows. | Starts at **$2,400/encoder seat/year** (~$200/seat/month; enterprise facility bundle from ~$18,000/year). | **14-day guided sandbox access** (limited to demo patient dataset and standard encoder lookups, no perpetual free tier). |
| **Quantros** | Healthcare quality, clinical safety event tracking, and risk-adjustment/coding analytics platform. | Starts at **$500 – $1,200/month per facility** (or ~$6,000 – $14,400/year base tier). | **30-day guided evaluation pilot** (limited to sample hospital department quality/coding data, no perpetual free tier). |
| **Enjoin** | Physician-led CDI, coding validation, risk adjustment (HCC), and revenue-integrity software and consulting. | Starts at **$1,500 – $3,000/month** for software/consultative tier (or ~$18,000/year base). | **30-day chart sample assessment** (limited to review of 100 historical patient charts, no perpetual free tier). |
| **CorroHealth Autonomous Coding** | AI-driven autonomous coding module (REVANT) within CorroHealth's RCM suite for emergency, radiology, and pathology departments. | Starts at **$1.15 – $2.50 per automated encounter** (or fixed departmental tiers from **$8,500/month**). | **30-day diagnostic proof-of-concept** (limited to 1,000 chart test run, no perpetual free tier). |
| **AGS Health** | Tech-enabled RCM company offering AI-assisted coding, CDI, charge capture, and AGS Coding Academy. | Starts at **$19 – $28/hour per dedicated coder** or **$1.40 – $2.60 per chart** (Coding Academy plans start at **$6,000/year**). | **30-day pilot program** for selected specialties (limited to 300 test encounters, no perpetual free tier). |
| **Access Healthcare** | AI medical coding, echo RCM automation suite, and healthcare business process outsourcing services. | Starts at **$1.20 – $2.40 per chart** or **4% – 7% of collections** (platform baseline starting at **$7,500/month**). | **30-day pilot workflow assessment** (limited to single billing workqueue evaluation, no perpetual free tier). |
| **GeBBS Healthcare Solutions** | iCode AI-assisted computer-assisted coding (CAC) platform, audit management, and RCM services. | Starts at **$1.30 – $2.50 per coded chart** or **$2,000/month per clinic facility**. | **30-day pilot audit trial** (limited to 250 chart audit benchmark sample, no perpetual free tier). |
| **HMS / Gainwell Technologies** | Enterprise Medicaid/Medicare integrity, coordination of benefits, payment accuracy, and claims coding audit engine. | Starts at **$5,000 – $15,000/month** for state agency/payer modules (or **5% – 12% contingency fee** on recovered overpayments). | **60-day proof-of-value data assessment** (limited to historical claims sample test run, no perpetual free tier). |



## Open-Source



The open-source medical coding ecosystem is much smaller than the commercial ecosystem.



There is currently no obvious open-source equivalent to a fully managed enterprise platform such as **CodaMetrix, Fathom, Nym, or AKASA** with the same combination of:



* Production-grade EHR integrations

* Coding rules

* Terminology licensing

* Coding compliance

* Human review

* Audit trails

* Payer-specific workflows

* Enterprise support

* HIPAA-compliant hosted infrastructure



However, there is a rapidly growing ecosystem of components that can be combined into an open medical coding stack.



### Complete / Near-Complete Open-Source Coding Projects



* **LLMCoder**



  * Domain-specific LLM framework for automated ICD-10 coding.

  * Uses fine-tuning and medical coding knowledge to map clinical documentation to ICD-10 codes.

  * Demonstrates automated coding from clinical text.

  * Reports both exact-code and category-level evaluation metrics.



* **medcoder**



  * Auditable medical coding pipeline for ICD-10 and CPT suggestions.

  * Uses hybrid retrieval, LLM-based extraction/coding, deterministic rules, and independent auditing.

  * Designed so that generated codes are constrained to actual catalog codes rather than freely generated.

  * Produces confidence, evidence, warnings, and an audit trail.



* **mimic-icd-coder**



  * Reproducible clinical NLP + MLOps pipeline for multi-label ICD-10 auto-coding.

  * Uses MIMIC-IV clinical data and supports TF-IDF and Bio_ClinicalBERT approaches.

  * Primarily a research/reference implementation rather than a production medical-coding product.



* **NeuroCode**



  * Deep-learning system for predicting ICD-10-CM codes from clinical text.

  * Uses a PyTorch TextCNN plus deterministic post-processing.

  * Provides a Streamlit interface for experimentation.



* **Vellum**



  * Auditable agentic ICD-10-CM/PCS autocoding project.

  * Uses LLM-based reasoning combined with deterministic verification.

  * Explicitly focuses on preventing fabricated evidence and making coding decisions auditable.

  * Released under MIT licensing.



## Open-Source Medical Coding Systems



### LLMCoder



```text

                   CLINICAL NOTE

                        │

                        ▼

                Clinical NLP / LLM

                        │

                        ▼

                 Clinical Concepts

                        │

                        ▼

                ICD-10 Candidate Set

                        │

                        ▼

                 Coding Model

                        │

                        ▼

                 ICD-10-CM CODES

```



LLMCoder is one of the more directly relevant open-source projects because it explicitly targets **automated ICD-10 coding** rather than merely performing generic medical NLP.



### medcoder



medcoder takes a more safety-oriented approach:



```text

Clinical Note

     │

     ▼

Extraction

     │

     ▼

Hybrid Retrieval

(FAISS + BM25)

     │

     ▼

Candidate Code Whitelist

     │

     ▼

LLM Coding

     │

     ▼

Independent Auditor

     │

     ▼

Deterministic Rules

     │

     ▼

Reviewer-Ready Result

```



The important architectural idea is that the model does **not simply invent codes**. Candidate codes are retrieved from a real coding catalog and subsequent deterministic validation constrains the result.



### MIMIC-ICD-Coder



This project is particularly useful for researchers who want a reproducible benchmark:



```text

MIMIC-IV

   │

   ├── Clinical Notes

   │

   ├── Diagnoses

   │

   └── ICD-10 Labels

          │

          ▼

     Preprocessing

          │

          ▼

       TF-IDF

          │

          ▼

    Multi-label Classifier

          │

          ▼

      ICD-10 Codes

```



It provides a reproducible end-to-end research pipeline and explicitly distinguishes its MIMIC-IV/ICD-10 task from earlier MIMIC-III/ICD-9 benchmarks.



## Open-Source Clinical NLP



Not every open-source clinical NLP project is a medical coder.



However, these frameworks are important building blocks.



### medspaCy



* Clinical NLP framework built on spaCy.

* Supports clinical text processing, section detection, entity extraction, contextual rules, and clinical information extraction.

* Useful for extracting diagnoses, procedures, medications, anatomy, and other concepts before coding.



### scispaCy



* Scientific and biomedical NLP toolkit.

* Provides biomedical language models and entity-recognition capabilities.

* Useful as a preprocessing and concept-extraction layer.



### Apache cTAKES



* Apache clinical Text Analysis and Knowledge Extraction System.

* Open-source clinical NLP platform.

* Provides clinical concept extraction, terminology mapping, and pipeline infrastructure.

* One of the longest-running open clinical NLP ecosystems.



### CLAMP



* Clinical Language Annotation, Modeling, and Processing.

* Supports clinical NLP pipelines, annotation, concept extraction, and terminology mapping.



### QuickUMLS



* Approximate string matching system for linking clinical concepts to UMLS.

* Useful for mapping extracted clinical phrases to standardized concepts.



### Clinical NLP Pipeline



* Open-source clinical NLP implementation combining entity extraction, UMLS concept linking, ICD-10 mapping, and FHIR output.

* Uses components such as BioClinicalBERT, QuickUMLS, SNOMED CT, RxNorm, and LOINC.

* Useful as a reference architecture for a broader clinical-coding system.



```text

Clinical Text

      │

      ▼

   medspaCy

      │

      ▼

 Clinical NER

      │

      ▼

 QuickUMLS / UMLS

      │

      ├── SNOMED CT

      ├── ICD-10

      ├── RxNorm

      └── LOINC

      │

      ▼

 Structured Clinical Data

      │

      ▼

 Coding Engine

```



## Medical Language Models



Medical coding systems can use specialized biomedical and clinical language models.



### BioClinicalBERT



* Clinical-domain adaptation of BERT.

* Frequently used for clinical NLP and ICD coding research.

* Particularly useful for clinical text classification and information extraction.



### PubMedBERT



* Biomedical language model trained on PubMed data.

* Useful for biomedical and clinical NLP.



### ClinicalBERT



* Family of BERT models adapted to clinical notes.

* Commonly used in clinical NLP research.



### BioBERT



* Biomedical language model trained on biomedical corpora.

* Widely used for biomedical NLP tasks.



### GatorTron



* Large clinical language model developed for healthcare NLP research.

* Useful for clinical text understanding and downstream healthcare NLP tasks.



### OpenBioLLM



* Open biomedical language model family.

* Can be fine-tuned or prompted for clinical coding experiments.



### Fine-Tuned OpenBioLLM Medical Coding



* Open model specifically fine-tuned for ICD-10 generation from clinical text.

* Provides a practical starting point for experimenting with LLM-based medical coding.



## Medical Terminology & Coding Infrastructure



A production medical coding system needs considerably more than an LLM.



### ICD-10-CM



Used primarily for:



* Diagnoses

* Conditions

* Symptoms

* Diseases

* Clinical classifications



### ICD-10-PCS



Used primarily for:



* Inpatient procedures

* Hospital procedure coding



### CPT



Used for:



* Physician services

* Procedures

* Evaluation and management

* Medical services



### HCPCS



Used for:



* Supplies

* Durable medical equipment

* Certain services

* Medicare/Medicaid-related coding



### SNOMED CT



Clinical terminology used to represent:



* Diagnoses

* Findings

* Procedures

* Clinical concepts



### RxNorm



Standardized terminology for medications.



### LOINC



Standardized terminology for:



* Laboratory tests

* Measurements

* Clinical observations



### UMLS



Meta-terminology infrastructure connecting multiple biomedical vocabularies.



A powerful open coding architecture can therefore look like:



```text

                  CLINICAL DOCUMENT

                         │

                         ▼

                  Clinical NLP

                         │

                         ▼

                  Clinical Concepts

                         │

        ┌────────────────┼────────────────┐

        │                │                │

     SNOMED            RxNorm           LOINC

        │                │                │

        └────────────────┼────────────────┘

                         │

                         ▼

                   Coding Engine

                         │

             ┌───────────┼───────────┐

             │           │           │

          ICD-10-CM   ICD-10-PCS    CPT

             │           │           │

             └───────────┼───────────┘

                         │

                         ▼

                  Coding Validation

                         │

                         ▼

                  Human Coder Review

```



## Research & Auto-Coding Projects



Additional open-source or research-oriented projects worth tracking include:



* **CAML**



  * Convolutional Attention for Multi-Label classification.

  * Historically important for automated ICD coding research.



* **MultiResCNN**



  * Multi-filter convolutional architecture for automated ICD coding.

  * Important benchmark architecture for clinical note classification.



* **PLM-ICD**



  * Transformer-based approaches to automated ICD coding.

  * Useful for studying pretrained language models in clinical coding.



* **LAAT**



  * Label Attention model for automated ICD coding.

  * Focuses on label-specific attention mechanisms.



* **JointLAAT**



  * Improved label-attention architecture for ICD coding.



* **ICD Coding with Clinical Transformers**



  * Numerous research implementations use BERT, BioBERT, ClinicalBERT, and Longformer architectures for multi-label ICD coding.



* **NeuroCode**



  * Practical deep-learning implementation for ICD-10 prediction.



* **mimic-icd-coder**



  * Modern reproducible MIMIC-IV/ICD-10 pipeline.



* **Vellum**



  * Agentic and auditable ICD-10-CM/PCS approach.



## Coding Architecture



A modern Medical Coding AI platform can be represented as:



```text

                       EHR / EMR

                           │

                           ▼

                  Clinical Documentation

                           │

            ┌──────────────┼──────────────┐

            │              │              │

         Notes           Labs        Procedures

            │              │              │

            └──────────────┼──────────────┘

                           │

                           ▼

                    NLP / LLM Layer

                           │

             ┌─────────────┼─────────────┐

             │             │             │

          Diagnosis     Procedure     Clinical

          Extraction    Extraction    Context

             │             │             │

             └─────────────┼─────────────┘

                           │

                           ▼

                    Terminology Layer

                           │

       ┌───────────────────┼───────────────────┐

       │                   │                   │

    SNOMED              UMLS               RxNorm

       │                   │                   │

       └───────────────────┼───────────────────┘

                           │

                           ▼

                     Code Retrieval

                           │

              ┌────────────┼────────────┐

              │            │            │

           ICD-10-CM   ICD-10-PCS      CPT

              │            │            │

              └────────────┼────────────┘

                           │

                           ▼

                    Coding Validation

                           │

            ┌──────────────┼──────────────┐

            │              │              │

        Guidelines      Evidence       Confidence

            │              │              │

            └──────────────┼──────────────┘

                           │

                           ▼

                     Human Review

                           │

                           ▼

                   Final Coded Record

                           │

                           ▼

                    Claims / RCM

```



## Autonomous Medical Coding



The ultimate objective of many commercial platforms is:



```text

                 CLINICAL DOCUMENTATION

                          │

                          ▼

                     AI CODER

                          │

              ┌───────────┼───────────┐

              │           │           │

          Diagnosis    Procedure    Evidence

              │           │           │

              └───────────┼───────────┘

                          │

                    Coding Rules

                          │

                          ▼

                    Confidence

                          │

                 ┌────────┴────────┐

                 │                 │

             HIGH CONFIDENCE    LOW CONFIDENCE

                 │                 │

                 ▼                 ▼

             AUTO-CODE         HUMAN REVIEW

                 │                 │

                 └────────┬────────┘

                          │

                          ▼

                       CLAIM

```



The critical difference between a generic LLM and a production autonomous coder is **verification**.



A production system must answer:



> "Why is this code supported by the documentation?"



not merely:



> "What code seems likely?"



## Evidence-Grounded Coding



A strong open-source architecture should require every prediction to contain:



```text

Code

 │

 ├── Code Description

 │

 ├── Evidence Span

 │

 ├── Clinical Concept

 │

 ├── Coding Guideline

 │

 ├── Confidence

 │

 ├── Model Version

 │

 └── Audit Trail

```



Projects such as `medcoder` and Vellum explicitly pursue this kind of auditable architecture rather than treating the LLM output as inherently trustworthy.



## Medical Coding AI Capability Matrix



| Capability           | SaaS / Hosted Platforms     | Open-Source                           |

| -------------------- | --------------------------- | ------------------------------------- |

| ICD-10-CM            | CodaMetrix, Fathom, Nym     | LLMCoder, medcoder, research projects |

| ICD-10-PCS           | Enterprise CAC platforms    | Vellum / research                     |

| CPT                  | Major CAC / RCM platforms   | medcoder / research                   |

| HCPCS                | Enterprise coding platforms | Custom                                |

| Clinical NLP         | Most major platforms        | medspaCy, cTAKES, scispaCy            |

| Diagnosis Extraction | Strong                      | Strong research ecosystem             |

| Procedure Extraction | Strong                      | Strong research ecosystem             |

| Autonomous Coding    | Increasingly common         | Emerging                              |

| Human-in-the-loop    | Strong                      | Custom                                |

| Coding QA            | Strong                      | Custom                                |

| CDI                  | Strong                      | Possible                              |

| DRG Optimization     | Strong                      | Custom                                |

| HCC Coding           | Strong                      | Research/custom                       |

| Risk Adjustment      | Strong                      | Custom                                |

| EHR Integration      | Strong                      | Requires implementation               |

| FHIR                 | Increasingly common         | Strong building-block ecosystem       |

| UMLS                 | Usually integrated          | QuickUMLS / UMLS                      |

| SNOMED CT            | Usually integrated          | Available                             |

| Explainability       | Enterprise-grade            | Emerging                              |

| Audit Trail          | Strong                      | medcoder / Vellum                     |

| Self-hosting         | Limited                     | Strong                                |

| Source Code          | No                          | Yes                                   |

| Custom Model         | Vendor-dependent            | Strong                                |

| Custom Coding Rules  | Vendor-dependent            | Strong                                |

| Data Sovereignty     | Vendor-dependent            | Strong                                |

| Vendor Lock-in       | Medium–High                 | Lower                                 |

| Enterprise Support   | Strong                      | Community / commercial partners       |



## SaaS vs Open Source



### Commercial / SaaS Medical Coding AI



Best suited for organizations wanting:



* Managed infrastructure

* EHR integrations

* Coding compliance

* Vendor support

* Enterprise security

* Human coding workflows

* Audit capabilities

* Revenue-cycle integration

* Payer-specific workflows

* Managed terminology updates



Major examples:



**CodaMetrix, Fathom, Nym, AKASA, 3M M*Modal, CorroHealth, Omega Healthcare, Waystar, Clinithink, Claimable and Optum.**



### Open-Source Medical Coding



Best suited for:



* Research

* Prototyping

* Internal tooling

* Academic benchmarking

* Private deployments

* Custom coding workflows

* Model experimentation

* Building healthcare AI infrastructure

* Organizations wanting control over their data



Strong candidates include:



**LLMCoder, medcoder, MIMIC-ICD-Coder, NeuroCode, Vellum, Apache cTAKES, medspaCy, scispaCy, QuickUMLS and BioClinicalBERT-based systems.**



## Recommended Open-Source Shortlist



### Tier 1 — Direct Medical Coding



* **LLMCoder**

* **medcoder**

* **mimic-icd-coder**

* **Vellum**

* **NeuroCode**



### Tier 2 — Clinical NLP Infrastructure



* **Apache cTAKES**

* **medspaCy**

* **scispaCy**

* **QuickUMLS**

* **CLAMP**



### Tier 3 — Medical AI Models



* **BioClinicalBERT**

* **PubMedBERT**

* **BioBERT**

* **ClinicalBERT**

* **GatorTron**

* **OpenBioLLM**



### Tier 4 — Research Architectures



* **CAML**

* **MultiResCNN**

* **LAAT**

* **JointLAAT**

* **Transformer-based ICD coding**

* **Long-document clinical coding models**



## Open-Source Medical Coding Stack



A practical open-source stack could look like:



```text

                         EHR

                          │

                          ▼

                  Clinical Documents

                          │

                          ▼

                    Apache cTAKES

                    / medspaCy

                          │

                          ▼

                 Clinical Entity Extraction

                          │

                          ▼

                    QuickUMLS / UMLS

                          │

             ┌────────────┼────────────┐

             │            │            │

          SNOMED        RxNorm        LOINC

             │            │            │

             └────────────┼────────────┘

                          │

                          ▼

                  Medical LLM / BERT

                          │

             ┌────────────┼────────────┐

             │            │            │

        Diagnosis     Procedure     Evidence

             │            │            │

             └────────────┼────────────┘

                          │

                          ▼

                    Code Retrieval

                          │

                ┌─────────┼─────────┐

                │         │         │

             ICD-10-CM ICD-10-PCS CPT

                │         │         │

                └─────────┼─────────┘

                          │

                          ▼

                  Rule-Based Validator

                          │

                          ▼

                    LLM Auditor

                          │

                          ▼

                  Confidence Scoring

                          │

                          ▼

                    Human Reviewer

                          │

                          ▼

                       Claim

```



## Open-Source Medical Coding Opportunities



The commercial market is increasingly moving from:



```text

Computer-Assisted Coding

          │

          ▼

AI-Assisted Coding

          │

          ▼

Autonomous Coding

          │

          ▼

Autonomous Revenue Cycle

```



This creates substantial opportunities for open-source infrastructure.



Potential projects include:



1. **Open-source autonomous medical coder**

2. **Open-source ICD-10 coding engine**

3. **Open-source CPT coding engine**

4. **Open-source coding QA engine**

5. **Open-source CDI assistant**

6. **Open-source HCC coding engine**

7. **Open-source DRG optimization engine**

8. **Open-source medical terminology server**

9. **Open-source coding evidence engine**

10. **Open-source coding audit trail**

11. **Open-source medical coding benchmark**

12. **Open-source coding evaluation framework**

13. **Open-source FHIR coding service**

14. **Open-source medical coding RAG**

15. **Open-source coding agent**

16. **Open-source autonomous claims preparation**

17. **Open-source coding rules engine**

18. **Open-source coder-in-the-loop platform**



### Particularly Interesting Architecture



```text

                     OPEN MEDICAL CODER

                            │

       ┌────────────────────┼────────────────────┐

       │                    │                    │

       ▼                    ▼                    ▼

   Clinical NLP         Medical LLM        Terminology

       │                    │                    │

       └────────────────────┼────────────────────┘

                            │

                            ▼

                     Evidence Engine

                            │

                            ▼

                    Candidate Retrieval

                            │

        ┌───────────────────┼───────────────────┐

        │                   │                   │

     ICD-10-CM           ICD-10-PCS            CPT

        │                   │                   │

        └───────────────────┼───────────────────┘

                            │

                            ▼

                     Coding Rules

                            │

                            ▼

                       AI Auditor

                            │

                            ▼

                    Confidence Score

                            │

              ┌─────────────┴─────────────┐

              │                           │

          Auto-Code                   Human Review

              │                           │

              └─────────────┬─────────────┘

                            │

                            ▼

                        CLAIM / RCM

```



The most compelling opportunity is arguably **not another medical LLM**, but an open-source **coding control plane** that combines terminology retrieval, coding rules, evidence grounding, model orchestration, auditing, and human review.



## Research Benchmarking



Medical coding AI should be evaluated using more than simple accuracy.



Useful metrics include:



| Metric              | Purpose                                  |

| ------------------- | ---------------------------------------- |

| Exact Code Match    | Measures exact coding correctness        |

| Category Accuracy   | Measures higher-level coding correctness |

| Micro F1            | Multi-label coding performance           |

| Macro F1            | Performance across rare/common codes     |

| Precision@K         | Quality of top predictions               |

| Recall@K            | Coverage of relevant codes               |

| AUC                 | Ranking discrimination                   |

| Evidence Accuracy   | Whether supporting evidence is correct   |

| Hallucination Rate  | Invalid/fabricated output rate           |

| Abstention Rate     | Frequency of safe human escalation       |

| Human Override Rate | How often coders reject AI output        |

| Coding Time         | Operational efficiency                   |

| DRG Accuracy        | Hospital reimbursement implications      |

| Audit Agreement     | Agreement with expert reviewers          |



Research projects such as `mimic-icd-coder` already expose detailed multi-label metrics such as Micro F1, Macro F1, Precision@K, AUC and AUPRC.



## Human-in-the-Loop Coding



A robust production architecture should **not force AI to code every chart**.



```text

                    AI CODER

                       │

                       ▼

                 Confidence Score

                       │

             ┌─────────┴─────────┐

             │                   │

          HIGH                  LOW

             │                   │

             ▼                   ▼

        Auto-Code            Human Coder

             │                   │

             └─────────┬─────────┘

                       │

                       ▼

                 Final Submission

```



This allows organizations to gradually increase automation:



```text

0% AI

  │

  ▼

AI Suggestions

  │

  ▼

AI + Human Review

  │

  ▼

High-Confidence Auto Coding

  │

  ▼

Selective Human Review

  │

  ▼

Autonomous Coding

```



## How to Contribute



1. Fork the repo.

2. Add or edit entries in `README.md`.

3. Keep the existing formatting style.

4. Include the official website or GitHub repository where appropriate.

5. Clearly identify whether the project is:



   * SaaS / Hosted

   * Commercial

   * Open-source

   * Open-core

   * Research

   * Clinical NLP infrastructure

   * Medical coding system

   * Medical language model

   * Terminology infrastructure

6. For open-source projects, preferably include the license.

7. Distinguish an actual coding engine from a general clinical NLP framework.

8. Avoid presenting research prototypes as production-ready medical systems.

9. Submit a PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



* This is a **community-curated** list — not exhaustive and not an endorsement.

* Medical coding is a regulated and highly consequential healthcare workflow.

* AI-generated codes should be validated according to applicable organizational, payer, regulatory, and professional requirements.

* Open-source projects listed here may be research projects and may **not be suitable for clinical or revenue-cycle production**.

* A medical NLP model is not automatically a medical coding system.

* A model that predicts ICD-10 codes does not necessarily support ICD-10-CM coding guidelines, ICD-10-PCS, CPT, HCPCS, DRGs, HCCs, or payer-specific requirements.

* Coding terminology, coding guidelines, reimbursement rules, and code sets change over time.

* CPT is proprietary and subject to licensing restrictions; organizations must obtain appropriate rights before using CPT content commercially.

* Clinical datasets such as MIMIC and other research datasets may have specific access, licensing, privacy, and data-use requirements.

* Never use restricted clinical datasets outside their permitted use.

* Production deployments require appropriate security, privacy, access control, audit logging, monitoring, validation, and healthcare compliance.

* HIPAA compliance is not automatically provided merely because software is open-source or self-hosted.

* Inclusion of a project does not imply regulatory approval, clinical validation, reimbursement approval, HIPAA certification, or production readiness.

* Product names, ownership, pricing, features, licensing, and availability can change over time.

* Always verify the current repository, license, terminology sources, model license, dataset license, maintenance activity, and commercial terms before adoption.



---



**Made for healthcare AI researchers, medical coders, CDI teams, revenue-cycle organizations, health systems, developers, open-source contributors, and anyone building the next generation of explainable and auditable medical coding infrastructure.**



Let's make medical coding AI more **open, auditable, evidence-grounded, interoperable, customizable, and human-centered**.
