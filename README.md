# Smart Research Assistant (SRA)

## 🌟 Overview
Smart Research Assistant (SRA) is a multi-agent research automation system powered by Google’s AI Agent Development Kit (ADK). It transforms a user query into a structured, multi-step research output through query analysis, web research, conceptual explanation, analytical evaluation, and synthesis.

## 📌 Problem Statement
The world is flooded with online data, scientific papers, and technical documentation. Traditional search engines and single-pass LLM responses struggle to produce deep, structured, multi-stage reasoning.  
**Goal:** Automate the research workflow so users instantly receive reliable, structured, research-grade insights.

## 🤖 Why Agents?
Agents enable:
- **Specialization** of tasks  
- **Orchestration** via a Root Orchestrator  
- **Parallel execution** for efficiency  
- **Memory-aware reasoning**  
- **Scalable modularity**  

This results in far more accurate and structured research outputs.

## 🏗️ Architecture

### 🔵 System Components
- **RootResearchOrchestrator**  
- **QueryUnderstandingAgent**  
- **WebResearchAgent**  
- **ExplainConceptAgent**  
- **StrengthWeaknessAgent**  
- **ResearchSynthesizerAgent**  
- **Memory Manager**  
- **InMemoryRunner**

### 📊 Architecture Diagram
*(Insert diagram here)*

## 🎬 Demo

**Query:**  
“Sleep disorder detection using multimodal physiological signals”

**Pipeline Steps:**
1. Query interpretation  
2. Web research  
3. Concept explanation  
4. Strength & weakness analysis  
5. Synthesis into final report  
6. Memory update  

## 🛠️ Technologies Used
- Google AI ADK  
- Gemini 2.x Flash  
- Python (async pipelines)  
- Custom tools & memory management  

## 📁 Repository Structure
```
/smart-research-assistant
│
├── notebooks/
│   └── SRA.ipynb
├── diagrams/
├── assets/
├── README.md
└── requirements.txt
```

## 🚀 Future Improvements
- Real web search  
- Citation extraction  
- PDF/document ingestion  
- Vector memory  
- Web dashboard  
- Cloud deployment  

## 📜 License
MIT License (recommended)

## 🙌 Acknowledgments
- Google AI ADK  
- Gemini models  
