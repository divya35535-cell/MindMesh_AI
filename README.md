# MindMesh AI — Intelligent Personal AI Workspace

MindMesh AI is an advanced BTech CSE project prototype that combines an AI workspace concept, smart task planner, document library, knowledge graph, and productivity insights in one responsive website.

## Run it in VS Code (beginner-friendly)

**No Node.js, npm, database, or API key is needed for this demo version.**

1. Download and extract `MindMesh-AI.zip`.
2. Open VS Code.
3. Select **File → Open Folder** and choose the extracted `MindMesh-AI` folder.
4. Open `index.html`.
5. Right-click inside the editor and choose **Open with Live Server** if you have the Live Server extension installed.
   - Or simply double-click `index.html` to open it in your browser.

## Working prototype features

- Responsive dashboard and navigation
- AI Workspace with local demo responses
- Smart task planner: add, complete, filter, and delete tasks
- Focus session timer
- Document library with search and local text/Markdown/CSV file upload
- Interactive knowledge graph with selectable concepts
- Productivity analytics dashboard
- Mobile-responsive layout

## Important project scope

This version is a **frontend prototype**. The assistant currently uses local demo responses; it does not call a real AI model. Analytics are illustrative, and tasks/documents are stored in browser memory for the current session. PDF parsing, persistent accounts/database, real model integration, and retrieval-augmented generation (RAG) are planned backend extensions.

## Suggested advanced development roadmap

1. **Backend:** Python FastAPI with REST endpoints.
2. **Database:** PostgreSQL for users, tasks, documents, and conversations.
3. **Real AI assistant:** connect an LLM provider from the backend; keep API keys out of frontend code.
4. **Document RAG:** extract PDF/text, chunk documents, create embeddings, retrieve relevant passages, and cite source snippets.
5. **Knowledge graph:** persist entities and relationships; add graph search and provenance.
6. **Predictive analytics:** train/evaluate a model on suitable real or public data; report actual metrics rather than demo values.
7. **Security:** authentication, authorization, upload validation, file limits, and safe handling of user data.

## Suggested project statement

MindMesh AI is an intelligent personal workspace designed to reduce information fragmentation by connecting documents, ideas, and tasks. It aims to help users retrieve relevant knowledge, convert goals into structured plans, and understand productivity patterns through an integrated, explainable interface.

## Suggested project objectives

- Build a responsive, accessible full-stack application.
- Provide AI-assisted planning and document question answering.
- Connect related concepts in a visual knowledge graph.
- Evaluate retrieval relevance and task-planning usefulness.
- Provide transparent limitations and secure data handling.

## File structure

```text
MindMesh-AI/
├── index.html
├── styles.css
├── app.js
└── README.md
```

## Academic integrity note

This prototype is a starting point. Understand the code, adapt the design and scope, and document which features are implemented versus proposed in your report and viva.
