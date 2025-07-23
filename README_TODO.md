# GPT-Researcher Team Project

## 📚 Project Description

**GPT-Researcher** is an autonomous research agent.  
- Users enter a research question/topic.
- The backend fetches data from the web (via Tavily API), organizes sub-questions, and generates a long, citation-rich report using OpenAI GPT.
- The frontend provides a beautiful UI to interact with the system, display reports, and manage research history.

---

## 🚦 Project Phases & Progress

| Phase    | Status        | Notes                            |
|----------|--------------|----------------------------------|
| Setup    | ✅ Complete   | Python/Node.js/Env/GitHub setup  |
| Backend  | ✅ Complete   | FastAPI backend running, tested  |
| Frontend | 🟡 Started    | Static HTML done, React upgrade now |
| Extras   | ⬜ Not started| Export/report/history/UX         |
| Deploy   | ⬜ Not started| Render/Vercel etc.               |
| Docs     | ⬜ Not started| Readme/screenshots               |

---

## 🧑‍💻 **Task Assignments**

### **Teammate 1 — UI Framework & Layout**
- Set up React app (`create-react-app` or `Vite`)
- Install and configure TailwindCSS (or Material-UI)
- Implement basic app layout: header, sidebar, main content
- Add navigation if needed

**Branch:** `feature/ui-layout`

---

### **Teammate 2 — Input Form & API Connection**
- Build the research query input form (topic, type, tone, etc)
- Connect form to backend `/report/` endpoint using Axios/fetch
- Implement loader/spinner for async calls
- Show error/success notifications

**Branch:** `feature/input-api`

---

### **Teammate 3 — Report Display & Formatting**
- Create component to display the AI-generated research report
- Format output for readability: headings, bullets, sources
- Add nice styling
- (Optional) Add "Export to PDF/Markdown" button

**Branch:** `feature/report-display`

---

### **Teammate 4 — Research History & UI Extras**
- Implement research history panel (store/display old reports)
- Add dark/light mode toggle
- Add robust error handling and user-friendly messages
- "History" page/component for viewing/running past research

**Branch:** `feature/history`

---

## 🏗️ **Git & GitHub Workflow**

### **A. Cloning the Project**

```bash
git clone https://github.com/dhruvigaira/gpt-researcher-project.git
cd gpt-researcher-project


**B. Checking Out Your Branch**
