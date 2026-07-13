# Kunal Singh

### Instrumentation & Control Engineering @ NSUT Delhi | Full-Stack Dev | AI/ML Systems Engineer

![Typing SVG](https://readme-typing-svg.demolab.com/?lines=Data+Structures+%26+Algorithms;Backend+Development;AI%2FML+Engineering;RAG+Systems;Vector+Databases;Systems+Design&font=Fira+Code&center=true&width=600&height=45&color=58A6FF&vCenter=true&pause=1000&size=22)

---

## 🚀 About Me

I enjoy understanding how systems work from the ground up — from low-level embedded firmware and computer architecture to full-stack web apps, databases, and now AI/ML engineering. I'm particularly focused on **production-grade RAG systems**, **cost-efficient infrastructure**, and **systems thinking**. Most of my time goes into DSA, systems-oriented projects, and building scalable applications that balance performance, cost, and reliability.

- 🏆 **Goldman Sachs Hackathon 2026** — Top 2.5% out of 20,000+ participants
- 🌍 **HPAIR Delegate** — Selected for Harvard's global leadership conference on AI & emerging tech
- 🧠 **LeetCode** — 200+ problems solved in C++ (Trees, Graphs, DP, Backtracking)
- 🤖 **AI/ML Engineering** — Building cost-efficient RAG applications with comprehensive evaluation pipelines

---

## 🎯 Featured Projects

### 🔬 **Cost-Efficient RAG Application with LLM-as-Judge Evaluation**
**[Repository](https://github.com/Kunalsingh7116-git/rag-assignment)** | **Status: Production-Ready**

A comprehensive retrieval-augmented generation (RAG) system demonstrating production engineering at scale.

**Key Achievements:**
- ✅ **94-97% cost savings** vs managed services (LanceDB self-hosted vs Pinecone Pro)
- ✅ **85% Recall@5** with strong nDCG@5 (0.68) and Context Precision (80%)
- ✅ **4.2/5 Faithfulness score** with minimal hallucination (<5%)
- ✅ **600ms p95 latency** (E2E including judge evaluation)
- ✅ **92% judge consistency** across repeated evaluations
- ✅ **Position bias mitigated** (flip rate 8%→3%)

**Technical Stack:**
- **Vector Store:** LanceDB (self-hosted, Arrow-native)
- **Embeddings:** all-MiniLM-L6-v2 (384-dim, local inference)
- **Retrieval:** Dense search + CrossEncoder reranking (+17% Recall improvement)
- **LLM:** Claude 3.5 Sonnet (production) / Gemini Flash (development)
- **Judge:** Claude 3.5 Sonnet with structured verdicts (faithfulness, relevance, completeness)
- **Metrics:** Recall@k, MRR, nDCG@k, Context Precision, Hit Rate, LLM-based answer quality
- **Framework:** FastAPI, Pydantic, LanceDB, sentence-transformers
- **Infrastructure:** Docker-ready, config-driven (dev/prod modes)

**Scale Analysis:**
| Vectors | LanceDB | Pinecone Pro | Savings |
|---------|---------|--------------|---------|
| 100K | $15/mo | $299/mo | **95% cheaper** |
| 1M | $50/mo | $1500/mo | **94% cheaper** |
| 10M | $200/mo | $7500/mo | **97% cheaper** |

**Design Decisions:**
- Chunk size optimization: 500 tokens (vs 300 fragmented / 1000 noisy)
- Idempotent re-ingestion using SHA-256 chunk hashing
- Context-only prompting to prevent hallucinations
- Separate judge/generator to reduce self-enhancement bias
- Multi-scale cost comparison with clear assumptions

**What This Project Demonstrates:**
1. **Systems thinking:** Choosing cost-efficient infrastructure without sacrificing quality
2. **Honest evaluation:** Not inflating metrics; realistic scores (4.2/5 not 5/5)
3. **Production readiness:** Docker support, config-driven, auditable logs
4. **Bias awareness:** Position bias reduction (8%→3%), inter-run agreement tracking
5. **Reproducibility:** Anyone can clone and run in <10 minutes

---

## 🧠 Languages & Skills

[![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![JavaScript](https://img.shields.io/badge/JavaScript-111111?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](https://github.com/Kunalsingh7116-git)
[![Arduino C](https://img.shields.io/badge/Arduino_C-00979D?style=for-the-badge&logo=arduino&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://github.com/Kunalsingh7116-git)

---

## 🤖 AI/ML & Data Engineering

[![LanceDB](https://img.shields.io/badge/LanceDB-FF6B6B?style=for-the-badge&logo=database&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![LLMs](https://img.shields.io/badge/LLMs_(Claude,_Gemini)-412991?style=for-the-badge&logo=openai&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![RAG](https://img.shields.io/badge/RAG_Systems-FF9500?style=for-the-badge&logo=books&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![Evaluation Metrics](https://img.shields.io/badge/IR_Metrics_(nDCG,_MRR)-4CAF50?style=for-the-badge&logo=chartjs&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![Vector Search](https://img.shields.io/badge/Vector_Search-5C7CFA?style=for-the-badge&logo=analytics&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![Embedding Models](https://img.shields.io/badge/Embeddings_(MiniLM,_etc)-6366F1?style=for-the-badge&logo=tensorflow&logoColor=white)](https://github.com/Kunalsingh7116-git)

---

## ⚙️ Frameworks & Technologies

[![React](https://img.shields.io/badge/React-111827?style=for-the-badge&logo=react&logoColor=61DAFB)](https://github.com/Kunalsingh7116-git)
[![Node.js](https://img.shields.io/badge/Node.js-111111?style=for-the-badge&logo=nodedotjs&logoColor=3C873A)](https://github.com/Kunalsingh7116-git)
[![Express](https://img.shields.io/badge/Express-1E1E1E?style=for-the-badge&logo=express&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![MongoDB](https://img.shields.io/badge/MongoDB-052E16?style=for-the-badge&logo=mongodb&logoColor=22C55E)](https://github.com/Kunalsingh7116-git)
[![MySQL](https://img.shields.io/badge/MySQL-0B1120?style=for-the-badge&logo=mysql&logoColor=3E9BFF)](https://github.com/Kunalsingh7116-git)
[![Pydantic](https://img.shields.io/badge/Pydantic-E8336A?style=for-the-badge&logo=python&logoColor=white)](https://github.com/Kunalsingh7116-git)

---

## 🛠️ Tools & Platforms

[![Git](https://img.shields.io/badge/Git-111111?style=for-the-badge&logo=git&logoColor=F05032)](https://github.com/Kunalsingh7116-git)
[![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![Linux](https://img.shields.io/badge/Linux-111111?style=for-the-badge&logo=linux&logoColor=FCC624)](https://github.com/Kunalsingh7116-git)
[![Arduino IDE](https://img.shields.io/badge/Arduino_IDE-00979D?style=for-the-badge&logo=arduino&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)](https://github.com/Kunalsingh7116-git)

---

## 💡 Core Competencies

**Systems Engineering:**
- Production-grade system design (cost, latency, scalability tradeoffs)
- Vector database evaluation and optimization
- Idempotent data pipelines
- Configuration-driven architecture (dev/prod modes)

**AI/ML Engineering:**
- Retrieval-Augmented Generation (RAG) systems
- LLM-as-Judge evaluation pipelines with bias detection
- Embedding model selection and evaluation
- Retrieval metrics (Recall@k, MRR, nDCG, Context Precision)
- Hallucination prevention through context grounding

**Software Engineering:**
- Full-stack development (frontend, backend, database)
- API design (FastAPI, REST)
- Data validation (Pydantic)
- Error handling and fallback strategies
- Comprehensive testing and reproducibility

**Data Structures & Algorithms:**
- Trees, Graphs, Dynamic Programming, Backtracking
- 200+ LeetCode problems solved
- Competitive programming mindset

---

## 📫 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kunal-singh-524360314)
[![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kunalsingh7116-git)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kunal.singh.ug24@nsut.ac.in)

---

## 🎓 Currently Learning

- Distributed systems and scalability patterns
- Advanced LLM evaluation and bias detection
- Cost optimization in ML infrastructure
- Multi-region deployment and fault tolerance

---

**Last Updated:** July 2026 | Always open to discussing systems design, AI/ML engineering, and production challenges!
