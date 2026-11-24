<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=170&color=0:1f6feb,100:8957e5&text=Yuri%20Ramos&fontColor=ffffff&fontSize=46&fontAlignY=36&desc=IA%20aplicada%20ao%20desenvolvimento%20de%20software&descSize=17&descAlignY=58" alt="Yuri Ramos" width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/yuri-ramos-c-campos"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/YuriRamos__"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <img src="https://img.shields.io/badge/Paranaguá,_PR-2b3137?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Paranaguá, PR" />
</p>

Analista de Sistemas Pleno na kie-tec, com pós-graduação em Machine Learning e Inteligência Artificial. Desenvolvo software com Python e TypeScript, utilizando modelos de linguagem (LLM) como aceleradores do ciclo de desenvolvimento, e atuo no desenvolvimento, análise e sustentação de automações RPA em UiPath.

## Atuação atual

- Desenvolvimento, análise e sustentação de automações (RPA) em UiPath para clientes de setores como indústria e financeiro.
- Participação no desenvolvimento de um motor de inteligência artificial voltado à análise e verificação de documentos.
- Frente interna dedicada a incorporar ferramentas de LLM às etapas de levantamento, desenvolvimento, análise e testes de software.

## Tecnologias

<p>
  <img src="https://skillicons.dev/icons?i=py,ts,js,cs,dotnet,fastapi,nodejs,express,react,nextjs,vite,sqlite,postgres,docker,git&perline=15" alt="Python, TypeScript, JavaScript, C#, .NET, FastAPI, Node.js, Express, React, Next.js, Vite, SQLite, PostgreSQL, Docker, Git" />
</p>

**Inteligência artificial**

<p>
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude Code" />
  <img src="https://img.shields.io/badge/Anthropic_API-191919?style=flat-square&logo=anthropic&logoColor=white" alt="Anthropic API" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square" alt="ChromaDB" />
  <img src="https://img.shields.io/badge/MCP-555555?style=flat-square" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/LM_Studio-4338CA?style=flat-square" alt="LM Studio" />
  <img src="https://img.shields.io/badge/llama.cpp-555555?style=flat-square" alt="llama.cpp" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
</p>

**Automação e testes**

<p>
  <img src="https://img.shields.io/badge/UiPath-FA4616?style=flat-square&logo=uipath&logoColor=white" alt="UiPath" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />
  <img src="https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white" alt="Power Automate" />
  <img src="https://img.shields.io/badge/SharePoint-0078D4?style=flat-square&logo=microsoftsharepoint&logoColor=white" alt="SharePoint" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest" />
</p>

## IA aplicada: o que venho estudando e testando

### Desenvolvimento assistido por agentes

- **Spec-Driven Development** com Spec Kit e tlc-spec-lean: plano, checks, construção e verificação por um agente independente, com validadores automáticos.
- **Custo de orquestração de múltiplos agentes**: medição de tokens por etapa do fluxo. A troca de agente no meio da construção saiu 32% mais cara, e a correção feita por um agente novo custou 2,6 vezes mais do que quando volta para quem escreveu o código.
- **Harness template** para Claude Code, Cursor e Windsurf: skills, hooks de economia de contexto e servidores MCP prontos para iniciar um projeto novo.
- **Executor de roteiros de teste**: skill que aplica um plano de testes em `.docx` contra uma aplicação web real via Playwright MCP, gerando a cópia preenchida, evidências em screenshot e o resumo de bugs.

### Modelos locais

- **Local AI Hub**: dashboard que detecta o hardware da máquina (GPU, VRAM, RAM) e recomenda modelos e backends compatíveis (Ollama, llama.cpp com Vulkan, DirectML).
- **Plataforma de IAs locais com RAG**: gerenciamento de contextos e consulta a documentos com Ollama, ChromaDB, LangChain e Streamlit.
- **Model Router**: camada de orquestração que escolhe entre Claude, OpenAI, Gemini e modelos locais de acordo com o tipo de tarefa, o custo, o contexto e a disponibilidade.
- **Second Brain CLI**: agente local de memória e prioridades acionado em linguagem natural pelo terminal, sem que nenhum dado saia da máquina.

### Aplicações com LLM

- **Checa**: verificação de fatos a partir de um link, texto ou print, com veredito por afirmação e fontes visíveis (Next.js, PostgreSQL, API da Anthropic).
- **Sinal**: sales intelligence para uma agência local, com descoberta de leads a partir de dados abertos, score explicável e diagnóstico comercial gerado sob demanda (FastAPI, React).
- **Gerador de atas de reunião**: transforma transcrições em atas `.docx` no template oficial, com suporte a Anthropic, OpenAI, Gemini e Ollama.
- **Serinus**: sistema de balcão para uma gráfica (cadastros, orçamentos e pedidos), desenvolvido inteiramente com fluxo spec-driven e agentes.
- **Polymarket AI Trader**: experimento de análise de mercados de predição com múltiplos provedores de LLM e modo de simulação (dry-run).

## Formação

- MBA em Machine Learning e Inteligência Artificial, XP Educação (2022)
- Análise e Desenvolvimento de Sistemas, IFPR Paranaguá (2016–2019)

<img src="https://capsule-render.vercel.app/api?type=waving&height=90&color=0:1f6feb,100:8957e5&section=footer" alt="" width="100%" />
