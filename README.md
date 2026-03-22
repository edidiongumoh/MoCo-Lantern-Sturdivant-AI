
# 🏮 MoCo Lantern: Biomimetic Geospatial Intelligence
**Stigmergy-based Visualization & RAG-driven Policy Orchestration for Urban Resilience**

---

##  Research Thesis
MoCo Lantern explores the intersection of **Generative AI** and **Biomimetic Visualization** to solve fragmentation in municipal social service ecosystems. By applying stigmergy-based mapping where high-demand resources "glow" based on real-time request density—the system transforms static service directories into a living, proactive intelligence framework.

##  Key Technical Pillars

### **1. RAG-Driven Policy Co-Pilot**
* **Engine:** Gemini 1.5 Flash (utilizing 1M+ token long-context window for deep policy reasoning).
* **Vector Architecture:** ChromaDB with 768-dimensional embeddings to provide cited, verifiable eligibility guidance across complex SNAP, housing, and utility assistance datasets.
* **Latency:** Optimized retrieval and inference to under 3 seconds.

### **2. Bioluminescent Geospatial Visualization**
* **Framework:** Pydeck (WebGL-based) integrated into Streamlit.
* **Concept:** Implemented a "Bioluminescent Map" interface that uses cyan-node intensity to represent service demand patterns, mimicking deep-sea organism signaling to reveal administrative bottlenecks.

### **3. Synthetic Data Engineering**
* **Dataset:** Engineered an enhanced 50-record synthetic 311 Service Request database to test multi-field query accuracy and geospatial distribution.

##  Tech Stack & Development
* **AI Orchestration:** Gemini 1.5 Flash, Kiro AI Assistant.
* **Backend:** Python, ChromaDB.
* **Frontend/GIS:** Streamlit, Pydeck (High-performance WebGL).

---

##  Impact & Scalability
While piloted with Montgomery County (MoCo) datasets, the **Stigmergy-Visualization Engine** is platform-agnostic and designed to scale across any urban environment requiring real-time resource allocation and policy transparency.

---
> 🔗 **Part of the AI Research Portfolio of Edidiong Hector Umoh**
> Focused on the convergence of Agentic AI, Cyber-Physical Systems, and Social Good.
##  Quick Start

### Prerequisites
- Python 3.10+
- Gemini API Key ([Get one free](https://aistudio.google.com/app/apikey))

### Installation

1. **Clone the repository**
```bash
git clone <your-repo-url>
cd Sturdivant-AI-Lab-MoCo-Copilot
```

2. **Create and activate virtual environment**
```powershell
# Windows PowerShell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

```bash
# Mac/Linux
python -m venv .venv
source .venv/bin/activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Configure API key**
```bash
# Copy the example env file
cp .env.example .env

# Edit .env and add your Gemini API key
# GEMINI_API_KEY=your_key_here
```

5. **Generate synthetic data**
```bash
python src/seed_data.py
```

6. **Launch MoCo Lantern**
```bash
streamlit run src/main.py
```

The app will open at `http://localhost:8501`

##  Features

### Phase 1: Policy Co-pilot (RAG-Driven)
- ✅ Instant, cited answers to SNAP/Housing/Utility eligibility questions
- ✅ ChromaDB vector store with Montgomery County 311 data
- ✅ 100% citation requirement for public trust
- ✅ Retrieval-augmented generation with Gemini 1.5 Flash

### Phase 2: Multilingual Intake
- ✅ AI Screening Bot with auto-categorization
- ✅ Support for English, Spanish, Amharic (in data model)
- ✅ Generates "Symptom & Need" briefs for Case Managers

### Visual Identity: Bioluminescent Theme
- ✅ Stigmergy-based visualization with glowing nodes
- ✅ Resource trails showing collective staff activity
- ✅ Dark-mode interface with cyan/teal accent colors
- ✅ Urgency-based color coding (red for urgent, cyan for medium, teal for low)

## 📊 Architecture

```
MoCo Lantern
├── src/
│   ├── main.py              # Streamlit Command Center UI
│   ├── rag_pipeline.py      # RAG orchestration with Gemini
│   ├── data_adapter.py      # Modular data source abstraction
│   ├── seed_data.py         # Synthetic data generator
│   └── config.py            # Bioluminescent theme configuration
├── data/
│   └── resources.json       # 50 synthetic service requests
├── assets/
│   └── styles.css           # Bioluminescent CSS animations
├── docs/
│   └── PRD.md              # Product Requirements Document
└── chroma_db/              # Vector store (auto-generated)
```

## 🎬 Demo Workflow

1. **Launch the app** - See the bioluminescent map with 50 glowing resource nodes
2. **View metrics** - Total resources, urgent cases, average days open
3. **Select mode** - Choose "Case Manager Research" or "Client Intake"
4. **Ask a question** - "Does Progress Place have a food pantry?"
5. **Get AI response** - Instant answer with citations to official policy documents
6. **Explore the map** - Click nodes to see resource details with urgency-based colors

## 🔬 Innovation: Stigmergy-Based Visualization

Inspired by ant colonies and bioluminescent organisms, MoCo Lantern uses **stigmergy**—indirect coordination through environmental traces. High-demand resources "glow" brighter, creating visual "trails" that reveal community needs in real-time. This biomimetic approach helps case managers identify at-risk neighborhoods before crises peak.

## 🔐 Security & Ethics

- **Privacy**: 100% synthetic data for prototype demonstrations
- **Accountability**: Human-in-the-loop design—Case Managers verify AI summaries
- **Fidelity**: 100% citation requirement for all policy claims
- **Transparency**: All sources linked to official Montgomery County data

## 📈 Impact

MoCo Lantern addresses Montgomery County's social services challenge by:
- **Reducing research time** from hours to seconds for case managers
- **Breaking language barriers** with multilingual support
- **Visualizing service gaps** through bioluminescent mapping
- **Ensuring accuracy** with mandatory citation of official policies
- **Scaling support** without proportional staff increases

##  Hackathon Submission

**Event**: World Wide Vibes - Montgomery County GenAI Academy Hackathon  
**Team**: Sturdivant AI Lab  
**Author**: Edidiong Hector Umoh  
**Built with**: Kiro AI Assistant

##  License

This project is submitted for the World Wide Vibes Hackathon 2026.

##  Acknowledgments

- Montgomery County Open Data Portal (data inspiration)
- Google Gemini API (LLM capabilities)
- ChromaDB (vector storage)
- Streamlit (rapid prototyping)
- Kiro AI (development assistance)

---

**🏮 Illuminating pathways. Empowering communities. One query at a time.**
