# iceDQ1
# 🤖 AI Data Quality Agent

An interactive **AI-powered data quality monitoring tool** built with **LangChain, RAG, and Streamlit**.  
This project demonstrates how AI agents can be applied to **data observability and validation** — inspired by real-world data quality challenges faced in ETL, Data Warehouse, and BI systems.

🔗 **Live Demo**: [Streamlit App](https://your-app.streamlit.app)  
📂 **Repo**: [GitHub Repo](https://github.com/yourusername/ai-data-quality-agent)

---

## 🚀 Features
- 📂 **CSV Upload** → Load any dataset for analysis.
- ✅ **Automated Checks**:
  - Missing values  
  - Duplicate rows  
  - Schema mismatches  
  - Outlier detection (Isolation Forest)  
- 💬 **AI Agent (LangChain)**:
  - Ask natural language questions about your dataset.  
  - Example: *“Does the email column have missing values?”*  
- 📚 **RAG-powered Assistant**:
  - Retrieves rules/guidelines from a vector database.  
  - Example: *“What rules apply to the `amount` column?”*  
- 🖥️ **Streamlit UI** → clean and simple interface.

---

## 🛠️ Tech Stack
- **Python 3.9+**
- **Streamlit** – UI
- **LangChain** – Agent orchestration
- **Chroma / FAISS** – Vector store for RAG
- **OpenAI GPT** – LLM for reasoning
- **Pandas / NumPy / scikit-learn** – Data quality checks

---

## 📦 Installation

Clone the repo:
```bash
git clone https://github.com/yourusername/ai-data-quality-agent.git
cd ai-data-quality-agent
 
