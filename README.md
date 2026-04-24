# Azure-AI-103-reference-guide-resources-tips
Azure AI-103 (reference guide, resources, practice tests &amp; tips)
# Azure AI-103 Study Guide — Quick Reference 2026

> Microsoft Azure AI App and Agent Developer Associate | Replaces AI-102 (retires June 30, 2026)

---

## Exam at a Glance

| Detail          | Info                                          |
|-----------------|-----------------------------------------------|
| Exam Code       | AI-103 (Beta)                                 |
| Level           | Associate                                     |
| Passing Score   | 700 / 1000                                    |
| Replaces        | AI-102 (retires June 30, 2026)                |
| Format          | MCQ, hotspot, drag-drop, scenario-based       |
| Prep Time       | 4–8 weeks                                     |
| Coding Required | Yes — Python proficiency expected             |
| Delivery        | Online proctored or test center               |

AI-103 is the direct successor to AI-102. It shifts focus from general Azure AI service
implementation toward building generative AI applications and autonomous agents using the
unified Microsoft Foundry platform. It targets developers already familiar with Python
who want to specialize in agentic AI and intelligent application development.

---

## Exam Domain Breakdown

### Domain 1 — Plan and Manage Azure AI Solutions (25–30%)

Designing infrastructure for AI apps, selecting appropriate deployment options,
integrating with CI/CD pipelines, managing Microsoft Foundry hub and project architecture,
configuring security with managed identities and private endpoints, monitoring solutions,
and applying responsible AI governance practices.

### Domain 2 — Implement Generative AI and Agentic Solutions (30–35%)

Building multi-agent systems using the Foundry Agent Service and Semantic Kernel framework.
Covers prompt engineering, chain-of-thought evaluations, managing conversation memory,
tool calling and function calling, multi-agent orchestration, and the A2A and MCP protocols.
This is the highest-weighted domain — prioritize it in your study plan.

### Domain 3 — Implement Text Analysis and Speech Solutions (10–15%)

Extracting entities, topics, summaries, and structured JSON outputs using generative
prompting and Foundry Tools. Configuring detection of sentiment, tone, safety issues,
and sensitive content. Building text translation solutions using Azure Translator or
LLM-powered flows. Converting speech to text and text to speech for agentic interactions,
including integration of custom speech models as an agent modality.

### Domain 4 — Implement Computer Vision Solutions (10–15%)

Using multimodal models for visual understanding, interpreting visual input within prompts,
generating new visual outputs using generative models, and building production-ready
applications with vision capabilities on Microsoft Foundry.

### Domain 5 — Implement Information Extraction Solutions (10–15%)

Extracting information from documents, forms, images, audio, and video using multimodal
pipelines that combine OCR, layout analysis, and field extraction. Producing grounded
representations for agents and RAG using Azure Content Understanding. Implementing
analyzers that generate structured or markdown outputs for downstream reasoning.
Configuring vector search and hybrid search with Azure AI Search.

---

## AI-103 vs AI-102 — Key Differences

| Area                  | AI-102 (Old)                        | AI-103 (New)                          |
|-----------------------|-------------------------------------|---------------------------------------|
| Focus                 | Azure AI service integration        | Agentic AI and generative app dev     |
| Platform              | Individual Azure Cognitive Services | Microsoft Foundry (unified)           |
| Agents                | Limited coverage                    | Core domain — multi-agent systems     |
| RAG                   | Basic coverage                      | Deep coverage with vector/hybrid search|
| Orchestration         | Not covered                         | Semantic Kernel, A2A, MCP protocols   |
| Python                | Helpful                             | Required — SDK usage expected         |

---

## Azure Services and Tools to Know

**Microsoft Foundry**
Hub and project architecture, model deployment, agent orchestration, monitoring,
and responsible AI governance. Central to the entire exam.

**Azure OpenAI Service**
Model selection, prompt engineering, RAG patterns, multimodal capabilities,
and production deployment of generative applications.

**Semantic Kernel / Foundry Agent Service**
Building AI agents with tool calling, function calling, and multi-agent orchestration.

**Azure AI Search**
Vector search, hybrid search configuration, and grounding agents with external data.

**Azure AI Language and Speech**
Text analysis, sentiment detection, entity extraction, summarization, speech-to-text,
text-to-speech, and custom speech model integration.

**Azure Content Understanding**
Multimodal extraction from documents, images, audio, and video using OCR,
layout analysis, and field extraction pipelines.

**Azure AI Vision**
Visual understanding with multimodal models and image generation capabilities.

---

## Official Study Resources

| Resource              | Link                                                                                        |
|-----------------------|---------------------------------------------------------------------------------------------|
| Official Study Guide  | https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-103  |
| Exam Page             | https://learn.microsoft.com/en-us/credentials/certifications/exams/ai-103/                 |
| Official Course       | https://learn.microsoft.com/en-us/training/courses/ai-103t00                               |
| Learning Path: AI Apps & Agents | https://learn.microsoft.com/en-us/training/paths/get-started-ai-apps-agents/      |
| Microsoft Q&A         | https://learn.microsoft.com/en-us/answers/products/                                        |
| Community Hub         | https://techcommunity.microsoft.com/t5/artificial-intelligence-and/ct-p/AI                 |
| Exam Sandbox          | https://aka.ms/examdemo                                                                     |

---

## Practice Tests

| Resource            | Details                                                                                              |
|---------------------|------------------------------------------------------------------------------------------------------|
| SkillCertPro        | AI-103 Exam Questions 2026 — https://skillcertpro.com/product/microsoft-azure-ai-103-exam-questions-2026/ |
| Tutorials Dojo      | Detailed explanations and cheat sheets — https://tutorialsdojo.com/ai-103-azure-ai-app-and-agent-developer-associate-study-guide/ |
| Udemy (6 mock exams)| 600 scenario-based questions — https://www.udemy.com/course/ai-103-azure-ai-practice-exams/         |

---

## Exam Tips

- Domain 2 (Generative AI and Agentic Solutions) carries 30–35% of the exam weight —
  spend the most time here.
- Python proficiency is expected, especially for Foundry SDK usage and agent client
  application development.
- Understand RAG end-to-end: chunking, embedding, vector search, grounding, and
  response generation.
- Know the difference between single-agent and multi-agent architectures, and when
  to apply each.
- Expect heavy coverage of Azure AI Foundry, prompt engineering, function calling,
  agent orchestration, and responsible AI safeguards.
- Hands-on practice matters — use an Azure free account to work directly with
  Foundry, Azure OpenAI, and AI Search before exam day.
- Target 85% or above consistently on practice tests before scheduling the real exam.

---

## Prerequisites Recommended

- AI-901: Azure AI Fundamentals (foundational AI concepts)
- AZ-900: Azure Fundamentals (cloud basics)
- Practical experience with Python and Azure services

## Next Steps After AI-103

- AI-300: Azure AI MLOps Engineer
- AI-200: Azure AI Search and Knowledge Engineer (2026)

---

*Last updated: April 2026 | Based on official Microsoft AI-103 exam objectives*
