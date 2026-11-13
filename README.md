# SAGE – AI Content Pipeline Agent

**Sourced Automated Generative Education (SAGE)**

An AI-powered multi-agent system designed to help teachers and educators automate the creation of educational materials using Agentic AI, Large Language Models (LLMs), and Retrieval-Augmented Generation (RAG).

##  Project Overview

SAGE is an intelligent educational content generation pipeline that transforms a simple teaching topic into a complete educational package.

Instead of manually preparing lessons, presentations, and assessments, teachers can provide a topic and let a team of specialized AI agents handle the process.

The system generates:
- 10 educational presentation slides.
- 20 assessment questions with answer keys.
- PowerPoint (PPTX) presentations.
- Word (DOCX) documents.
- A downloadable ZIP package containing the generated materials.

##  System Architecture

SAGE follows a multi-agent architecture where an Orchestrator coordinates specialized agents throughout the content generation process.

### AI Agents

1. **Orchestrator Agent**
   - Receives the teacher's topic and requirements.
   - Coordinates the workflow.
   - Delegates tasks to specialized agents.
   - Manages communication between agents.

2. **Planning Agent**
   - Analyzes the requested topic.
   - Creates a structured educational content plan.
   - Defines the learning objectives and content organization.

3. **Research & RAG Agent**
   - Retrieves relevant information from external knowledge sources.
   - Uses Wikipedia and OpenAlex for research.
   - Uses embeddings and FAISS for semantic retrieval.
   - Provides grounded information for content generation.

4. **Content Generation Agents**
   - Generate educational presentation slides.
   - Create assessment questions and answer keys.
   - Organize the generated content into structured documents.

5. **Validation Agent**
   - Reviews the generated educational materials.
   - Evaluates content quality.
   - Applies a quality threshold of 85% before considering the output ready.

##  Workflow

Teacher Input → Orchestrator → Planning Agent → Research & RAG → Content Generation → Validation → Final Educational Package.

##  Tech Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| AI Models | GPT-4o-mini |
| Architecture | Multi-Agent Systems |
| AI Orchestration | Agentic AI |
| Knowledge Retrieval | RAG |
| Vector Search | FAISS |
| Embeddings | all-MiniLM-L6-v2 |
| Research Sources | Wikipedia, OpenAlex |
| Document Generation | PPTX, DOCX |
| Language Support | Arabic (RTL) |

##  Key Features

- Automated educational content generation.
- Multi-agent collaboration and task delegation.
- Research-grounded content generation using RAG.
- Automated question and answer generation.
- Quality evaluation and validation.
- Arabic Right-to-Left (RTL) document support.
- Exportable educational resources.

##  Project Goals

SAGE aims to reduce the time and effort teachers spend preparing educational materials, with a target of up to 80% reduction in preparation time.

It also demonstrates how Agentic AI can transform a traditional educational workflow into an intelligent, automated pipeline.

##  Team

Developed as a collaborative final project for the **Saudi Digital Academy Agentic AI Program**.

##  My Role

**Orchestrator Agent Developer**

My primary responsibility was working on the Orchestrator Agent, which coordinates the overall workflow, delegates tasks to specialized agents, and manages the execution of the educational content generation pipeline.

---

**SAGE – Turning educational ideas into complete learning materials with Agentic AI.**
