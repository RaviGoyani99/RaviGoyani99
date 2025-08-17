<!-- Neon Gradient Header -->
<p align="center">
  <img src="https://github.com/RaviGoyani99/RaviGoyani99/blob/main/artificial-intelligence-concept.jpeg" alt="AI Banner" width="100%" />
</p>

<!-- Typing intro -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=62F6FF&center=true&vCenter=true&width=900&lines=I+turn+data+and+models+into+products.;RAG+%7C+LLMOps+%7C+CV+%7C+NLP+%7C+MLOps.;Quality+%3E+quantity.+Observability+%26+evaluation+first." alt="typing intro">
</p>

<h1 align="center">Hi, I'm Ravi Goyani 👋</h1>
<p align="center">
  <a href="https://www.linkedin.com/in/ravi-goyani-030190199" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Ravi%20Goyani-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:your.email@example.com"><img alt="Email" src="https://img.shields.io/badge/Email-say%20hello-FF4D4D?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://your-portfolio.com" target="_blank"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-visit-111827?style=for-the-badge&logo=vercel&logoColor=white"></a>
  <img alt="Views" src="https://komarev.com/ghpvc/?username=YOUR_GITHUB_USERNAME&label=Profile+Views&color=8E2DE2&style=flat">
</p>

---

### 🚀 Mission
- Build trustworthy AI: measurable, reproducible, and observable.
- Bridge research → production: fast prototyping, rigorous evaluation, smooth deployment.
- Focus areas: RAG systems, small/efficient LLMs, computer vision, and MLOps.

---

### 🧠 AI/ML — What I Love Working On
<p align="center">
  <img src="https://img.shields.io/badge/RAG-pipelines-7C3AED?style=for-the-badge">
  <img src="https://img.shields.io/badge/LLM-Orchestration-1F2937?style=for-the-badge&logo=openai&logoColor=white">
  <img src="https://img.shields.io/badge/Multimodal-CV%20%E2%80%A2%20NLP-0EA5E9?style=for-the-badge">
  <img src="https://img.shields.io/badge/Evaluation-%F0%9F%94%8D%20metrics-06B6D4?style=for-the-badge">
  <img src="https://img.shields.io/badge/Explainability-XAI-14B8A6?style=for-the-badge">
  <img src="https://img.shields.io/badge/Monitoring-Drift%20%26%20Quality-22C55E?style=for-the-badge">
</p>

---

### 🧰 Core Stack

<b>Languages & Libraries</b>
<p align="center">
  <img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,numpy,pandas,opencv,matplotlib&theme=light" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/lightning-792EE5?style=flat-square&logo=pytorchlightning&logoColor=white"/>
</p>

<b>Generative AI</b>
<p align="center">
  <img src="https://img.shields.io/badge/HuggingFace-FFD21F?style=flat-square&logo=huggingface&logoColor=000"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=fff"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=fff"/>
  <img src="https://img.shields.io/badge/LlamaIndex-2E4053?style=flat-square&logo=readme&logoColor=fff"/>
  <img src="https://img.shields.io/badge/VectorDB-FAISS%20%7C%20Chroma%20%7C%20Milvus-0EA5E9?style=flat-square"/>
</p>

<b>MLOps & Infra</b>
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,fastapi,git,githubactions,linux,bash,aws,gcp,airflow&theme=light" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=fff"/>
  <img src="https://img.shields.io/badge/W%26B-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=000"/>
  <img src="https://img.shields.io/badge/DVC-945DD6?style=flat-square&logo=dvc&logoColor=fff"/>
  <img src="https://img.shields.io/badge/KServe-2B6CB0?style=flat-square"/>
  <img src="https://img.shields.io/badge/Ray-3B82F6?style=flat-square"/>
</p>

---

### 🧪 Mini Showcase (AI/ML)
- ⚡ RAG: Hybrid search + reranking + answer grading
- 🧩 Multimodal: CLIP/BLIP pipelines for image-text retrieval
- 🔎 Eval: Task-specific metrics, hallucination checks, guardrails

<p align="center">
  <a href="https://your-demo-link.com" target="_blank"><img src="https://img.shields.io/badge/Demo-RAG%20Playground-0ea5e9?style=for-the-badge&logo=streamlit&logoColor=white" alt="RAG demo"/></a>
  <a href="https://your-repo-link.com" target="_blank"><img src="https://img.shields.io/badge/Code-LLM%20Toolkit-8e2de2?style=for-the-badge&logo=github&logoColor=white" alt="LLM toolkit"/></a>
  <a href="https://your-notebook-link.com" target="_blank"><img src="https://img.shields.io/badge/Notebook-Computer%20Vision-22c55e?style=for-the-badge&logo=jupyter&logoColor=white" alt="CV notebook"/></a>
</p>

---

### 🧩 Example Pipeline (RAG, concise)
```python
from langchain_community.vectorstores import FAISS
from langchain.embeddings import HuggingFaceEmbeddings
from langchain_openai import ChatOpenAI
from langchain.chains import RetrievalQA

embed = HuggingFaceEmbeddings(model_name="sentence-transformers/all-MiniLM-L6-v2")
db = FAISS.from_texts(texts, embedding=embed)

llm = ChatOpenAI(model="gpt-4o-mini", temperature=0)
rag = RetrievalQA.from_chain_type(llm, retriever=db.as_retriever(search_kwargs={"k": 6}))

print(rag.run("What are the trade-offs of hybrid search for FAQs?"))
📈 GitHub Stats
<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=radical&hide_border=true&rank_icon=github" alt="GitHub Stats"/> <br/> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=radical&hide_border=true" alt="Top Languages"/> <br/> <img src="https://streak-stats.demolab.com?user=YOUR_GITHUB_USERNAME&theme=radical&hide_border=true" alt="GitHub Streak"/> <br/> <img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_GITHUB_USERNAME&theme=react-dark&hide_border=true" alt="Contribution Graph"/> </p>
🏆 Trophies
<p align="center"> <img src="https://github-profile-trophy.vercel.app/?username=YOUR_GITHUB_USERNAME&theme=dracula&no-frame=true&row=1&column=7" alt="GitHub Trophies"/> </p>
💬 Favorite line
“Ship value, not just models.”

🤝 Connect
<p align="center"> <a href="https://www.linkedin.com/in/ravi-goyani-030190199"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a> <a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Email-Contact-FF4D4D?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a> </p><!-- Footer Ribbon --><p align="center"> <img src="https://capsule-render.vercel.app/api?type=wave&color=0:4A00E0,100:8E2DE2&height=120&section=footer&animation=fadeIn" alt="footer wave"/> </p> ```
Want me to swap in your actual GitHub username, links, and a custom color palette? Tell me your username and any demo/portfolio URLs, and I’ll plug them in.
