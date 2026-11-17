# <img src="https://user-images.githubusercontent.com/1303154/88677602-1635ba80-d120-11ea-84d8-d263ba5fc3c0.gif" width="28px" height="28px" alt="oi"> Olá, eu sou o Rafael José 🧑‍💻

🎓 Estudante de **Ciência da Computação (3º período)** na **Universidade Federal de Goiás (UFG)**
🔬 **Pesquisador no [CEIA-UFG](https://ceia.ufg.br/)** (Centro de Excelência em Inteligência Artificial)
🧠 Áreas de interesse: **NLP** e **MLOps**

Gosto de levar modelos de linguagem do protótipo para algo confiável: com avaliação, métricas, testes automatizados e deploy reproduzível.

---

### 🚀 Projetos em destaque

#### 🌾 [Maestro Agrícola](https://github.com/vvvvvdal/maestro-agricola)
Interface *hands-free* para comandar maquinário agrícola autônomo com **visão, voz e confirmação por áudio**, usando óculos com IA. Desenvolvido pela equipe AgroTurtles para o **Programa AI Glasses Brasil 2026**, com MVP validado de ponta a ponta e artigo científico no formato IEEE.

- **Meu papel:** IA local, métricas e evidências.
  - Montei o corpus e a avaliação do classificador de intenções (`SPRAY`, `DOCK`, `UNDOCK`, `CONFIRM`, `CANCEL`, `UNKNOWN`).
  - Defini o limiar de confiança e o tratamento de ambiguidade.
  - Garanti a paridade entre a implementação de referência em Python e a versão em Kotlin.
  - Fiz o benchmark do **Qwen2.5-1.5B** (via `llama.cpp`) que embasou a escolha do modelo.
- **Stack:** Python · Qwen2.5 / llama.cpp · ROS 2 · Gazebo · Nav2 · Docker · GitHub Actions
- 📄 [Paper](https://github.com/vvvvvdal/maestro-agricola/blob/main/docs/paper/Maestro-Agricola-Paper.pdf) · 🎥 [Pitch](https://www.youtube.com/watch?v=T2leg-1uZu8)

#### 📚 [RAG Search Agent: legislação ANEEL](https://github.com/AyuHamano/rag-search-agent)
Sistema de busca inteligente com **Retrieval Augmented Generation** sobre a biblioteca de legislação da ANEEL, feito em equipe.

- Pipeline de ingestão: download de PDFs, extração de texto e tabelas, chunking por parágrafo e indexação vetorial.
- Embeddings `intfloat/multilingual-e5-base`, banco vetorial **Qdrant** e geração com **Gemini 2.5 Flash**.
- Interface em **Streamlit**, testes com **pytest**, script de avaliação do RAG e ambiente em **Docker Compose**.

#### 🐢 [TurtleBot MLOps: CI/CD para robótica](https://github.com/vvvvvdal/turtlebot-mlops-cicd)
Pipeline de CI/CD em que **o robô simulado é o teste**: a cada push, o GitHub Actions roda uma simulação no Turtlesim com um agente LLM local (Ollama + Qwen2.5). O deploy só é liberado se o robô chegar ao destino sem colidir.

---

### 🛠️ Tecnologias

**Linguagens**
<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C" />
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />

**IA e NLP**
<br>
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
<img src="https://img.shields.io/badge/Sentence_Transformers-FF6F00?style=for-the-badge" alt="Sentence Transformers" />
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge" alt="Qdrant" />
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini" />
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" />
<img src="https://img.shields.io/badge/llama.cpp-333333?style=for-the-badge" alt="llama.cpp" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />

**MLOps, robótica e ferramentas**
<br>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
<img src="https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white" alt="ROS 2" />
<img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest" />
<img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
<img src="https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white" alt="LaTeX" />
<img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VSCode" />

**Idiomas**
<br>
<img src="https://img.shields.io/badge/Português-Nativo-green?style=flat-square" alt="Português nativo" />
<img src="https://img.shields.io/badge/Inglês-Fluente-blue?style=flat-square" alt="Inglês fluente" />

---

### 📫 Contato

<div align="left">
  <a href="https://www.linkedin.com/in/rafael-marques-54a8b9351/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:rafaelfrapp@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="https://www.instagram.com/souzs.rafael_/" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
</div>
