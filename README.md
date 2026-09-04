<div align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0f172a,100:2563eb&text=Ansh%20Sahu&fontAlign=50&fontAlignY=36&fontSize=58&fontColor=ffffff&desc=AI%20Research%20%7C%20LLM%20Evaluation%20%7C%20Systems%20Engineering&descAlign=50&descAlignY=58&descSize=18" alt="Ansh Sahu" />

Portfolio LinkedIn Show Image

</div>
Research

BEng Computer Science, First Class Honours — Anglia Ruskin University, Cambridge (2026).

My dissertation was an empirical study of whether RAG grounding improves rubric alignment and trustworthiness in AI-generated feedback — evaluated against expert annotation across 100 reports. The central finding: RAG doesn't just improve alignment scores, it makes AI errors inspectable and contestable rather than hidden. Every feedback claim was traceable to a retrieved rubric passage, enabling human reviewers to interrogate outputs rather than accept them on faith.

This connects to a broader question I find compelling: what does it take for an AI system to be trustworthy rather than merely fluent?

Research Results — EduAIPlatform (BEng Dissertation, 76%)
Metric	Result	Threshold
RAG vs ungrounded rubric alignment	+13.2%	>10% ✅
AI-to-expert agreement	84%	>80% ✅
Inter-annotator agreement (Cohen's κ)	0.79	≥0.75 ✅
BERT classifier macro-F1	0.83	≥0.80 ✅
Confidence calibration (ECE)	0.038	<0.05 ✅
Cross-modal variance (text vs audio)	8.4%	<10% ✅
Moderation bypass events	0 / 100	0 ✅
Hallucination rate	3.2%	All claims traceable to retrieved passages

Supervised by Ashim Chakraborty. Evaluation corpus: 100 expert-annotated reports, two independent domain annotators, blind test set.

Projects
Project	What it is	Signal
EduAIPlatform	Empirical RAG vs ungrounded LLM evaluation — BEng dissertation	κ=0.79, ECE=0.038, LangGraph stateful routing, hybrid BM25+dense retrieval
applied-ai-multimodal-project	ML across 4 modalities with explainability	SHAP · LIME · Grad-CAM · DistilBERT · CNNs · UrbanSound8K
HR-Agent-Agentic-AI-Human-Resources-Platform	Enterprise agentic AI — built at Accenture	17 LLM tools · human-in-the-loop approvals · audit logging · semantic memory
NebulaKV	Distributed key-value store in C++20	Raft consensus · fault injection · P99 benchmarking · sanitizers · CI
InferX	C++23 AI inference runtime	DevSecOps · containerised · cloud-native deployment
coreml-inference-benchmarking-toolkit	PyTorch → CoreML + latency/P95/P99 measurement	Cross-path Python + Swift execution
Why These Projects Matter

EduAIPlatform is an empirical demonstration of three safety-relevant properties:

Traceability over fluency — RAG grounding means every AI claim links to a source; a 3.2% hallucination rate matters less than the fact that errors are findable
Oversight as a technical control — the confidence gate routes uncertain outputs to professor review; this is enforced by architecture, not policy
Graceful degradation — LangGraph fallback routing maintains audit-complete output when pipeline nodes degrade (validated in TC-12.3); silent failure is not acceptable in a governed system

NebulaKV + InferX cover the systems side: distributed consensus, failure-mode testing, P99 latency benchmarking, and production-grade C++20/23 — relevant to ML infrastructure and high-performance inference work.

Stack

Research & ML — Python PyTorch BERT ONNX Runtime scikit-learn DistilBERT SHAP LIME Grad-CAM

LLM & Agentic — LangChain LangGraph Ollama RAG ChromaDB MCP n8n

Backend & Data — FastAPI PostgreSQL Kafka Airflow dbt BigQuery

Systems — C++20/23 C#/.NET Docker GitHub Actions CMake GoogleTest

Frontend — React Next.js TypeScript

Open to

Empirical AI research collaboration — LLM evaluation, scalable oversight, model trustworthiness, ML systems. Based in Cambridge, UK. UK work authorised.

<div align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:2563eb,100:0f172a" alt="footer" /> </div>
