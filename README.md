# Hi, I'm Bernardo 👋

Welcome to my GitHub profile! I'm a **Software Developer focused on Web & Applied AI** and a **Systems Analysis and Development** student at **PUCRS**. I work mainly with **TypeScript, Node.js, and Python**, and I'm moving from front-end development into AI engineering.

My current focus is building **LLM-powered features for real products**, from cost-aware API integration to reusable AI workflows. I'm looking for my first opportunity as a **junior developer or intern** in AI-driven development, remote or on-site.

![GitHub stats](https://github-readme-stats.vercel.app/api?username=bernardosrodrigues12&show_icons=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=bernardosrodrigues12&layout=compact)

## 🛠️ Featured Projects

### 1. Cost Meter — LLM API Cost Benchmark
[Repository](https://github.com/bernardosrodrigues12/medidor-custo)

A TypeScript CLI that measures every LLM call (input, output, and thinking tokens, estimated cost, and latency) and saves the results to CSV, so model choices rest on data. It includes exponential-backoff retries for transient errors (429/500/503), fail-fast handling for deterministic errors, and an experiment comparing two Gemini models.

**Key finding:** thinking tokens are billed as output. Leaving them out of the cost formula underestimated cost by 5.8×.

<div style="display: inline-block"><br>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white">
  <img alt="Node" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white">
  <img alt="LLM APIs" src="https://img.shields.io/badge/LLM_APIs-412991?style=for-the-badge">
</div>

### 2. stream-classify-api — Streaming Support Message Classifier
[Repository](https://github.com/bernardosrodrigues12/stream-classify-api)

A Node.js + TypeScript API that classifies support messages with the Gemini API and streams the response via Server-Sent Events. Output is validated with Zod against closed categories and priorities. Retries use exponential backoff with jitter, only for retryable errors and only before the first token. Errors are typed (`code`, `message`, `retryable`), and a React interface consumes the stream and handles loading, partial, success, and error states.

<div style="display: inline-block"><br>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white">
  <img alt="Node" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
</div>

### 3. prompt-diff — Prompt Technique Benchmark
[Repository](https://github.com/bernardosrodrigues12/prompt-diff)

A controlled comparison of prompt engineering techniques for classifying support messages into five categories. The method uses a frozen dataset, temperature 0, decision criteria declared before validation runs, and a paired McNemar test.

**Key finding:** on a 30-case validation set (5 runs per case), v4 showed no statistically significant gain over v3. I documented that result instead of declaring a winner.

<div style="display: inline-block"><br>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img alt="Prompt Engineering" src="https://img.shields.io/badge/Prompt_Engineering-FF6F00?style=for-the-badge">
  <img alt="LLM APIs" src="https://img.shields.io/badge/LLM_APIs-412991?style=for-the-badge">
</div>

## 🚀 Skills

### Front-End 🖥️
<div style="display: inline-block"><br>
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img alt="HTML" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img alt="CSS" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
</div>

### Back-End 💻
<div style="display: inline-block"><br>
  <img alt="Node" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
</div>

### AI 🤖
<div style="display: inline-block"><br>
  <img alt="Prompt Engineering" src="https://img.shields.io/badge/Prompt_Engineering-FF6F00?style=for-the-badge">
  <img alt="LLM APIs" src="https://img.shields.io/badge/LLM_APIs-412991?style=for-the-badge">
  <img alt="Claude Code" src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge">
  <img alt="Google AI Studio" src="https://img.shields.io/badge/Google_AI_Studio-4285F4?style=for-the-badge&logo=google&logoColor=white">
</div>

### Tools 🖱️
<div style="display: inline-block"><br>
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">
  <img alt="Git" src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white">
  <img alt="VS Code" src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white">
</div>

## 🎓 Certificates
<div style="display: inline-block"><br>
  <a href="https://cursos.alura.com.br/user/be-srodrigues24/degree-angular-crie-aplicacoes-web-ageis-702263/certificate"><img alt="Angular certificate" src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white"></a>
  <a href="https://cursos.alura.com.br/user/be-srodrigues24/degree-typescript-desenvolva-front-end-produtividade-644154/certificate"><img alt="TypeScript certificate" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"></a>
  <a href="https://cursos.alura.com.br/user/be-srodrigues24/degree-html-css-674466/certificate"><img alt="HTML5 certificate" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"></a>
  <a href="https://cursos.alura.com.br/user/be-srodrigues24/degree-css-estilos-691591/certificate"><img alt="CSS3 certificate" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"></a>
  <a href="https://cursos.alura.com.br/user/be-srodrigues24/degree-js-backend-716073/certificate"><img alt="Node.js certificate" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white"></a>
  <a href="https://cursos.alura.com.br/user/be-srodrigues24/degree-linguagem-python-698571/certificate"><img alt="Python certificate" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"></a>
  <a href="https://cursos.alura.com.br/user/be-srodrigues24/course/git-github-dominando-controle-versao-codigo/certificate"><img alt="Git and GitHub certificate" src="https://img.shields.io/badge/Git_&_GitHub-E44C30?style=for-the-badge&logo=git&logoColor=white"></a>
</div>

[Full Certificate](https://cursos.alura.com.br/user/be-srodrigues24/fullCertificate/fc9d6d521b9987540fcd769a3476adf7)

**Additional courses:** Masterizando o ChatGPT | IA para Imagens — Adapta ONE

## 📖 What I'm Learning
- Applying **RAG** and **tool calling** in an ongoing project
- Deepening my knowledge of **prompt engineering** and **LLM APIs**
- Deepening my **Python** and **Node.js** back-end skills

## 🌟 What I'm Working On

I'm currently building a **RAG and tool-calling** project and refining my LLM projects, including **Cost Meter** and **prompt-diff**. Feel free to explore my repositories and share feedback! 😸

## 🎯 Goal

To land my first opportunity as a **junior developer or intern** in AI-driven development, remote or on-site. If you're interested in collaborating, or just want to talk about technology and AI, I'm always open to new connections! 🤝

## 📫 Get in Touch

You can find me on:

<a href="https://www.linkedin.com/in/bernardo12"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> 💼

<a href="mailto:be.srodrigues24@gmail.com"><img alt="Gmail" src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a> 📧

<a href="https://www.instagram.com/be_srodrigues"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a> 📸

Thanks for visiting my profile! 😸

---

*P.S.: I'm always learning and adapting, so don't be surprised if you find something new here!*
