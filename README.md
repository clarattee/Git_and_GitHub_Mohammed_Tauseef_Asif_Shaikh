# DevOps Git & GitHub Workflow Assignment

**Student Name:** Mohammed Tauseef Asif Shaikh  
**Course:** DevOps Engineering | Assignment Submission  
**Project Base:** Flask Web Application with MongoDB Cloud Integration  

---

## 📌 Project Objectives
This repository contains a complete, hands-on implementation of the full Git version control workflow, detailing development environments, branch management, conflict handling, and history rewriting.

### Key Milestones Completed:
1. **Task 1: Repository Architecture** - Setup local repositories via Miniconda on an administrative-restricted environment and managed individual username development branches.
2. **Task 2: Targeted Merge Conflicts** - Intentionally forced, tracked, and resolved data schema variations on a secondary `_new` branch.
3. **Task 3: Parallel Track Operations** - Separated frontend interface designs (`master_1`) from backend MongoDB database routes (`master_2`) simultaneously.
4. **Task 4: Structural History Rewriting** - Executed sequential atomized commits, rolled back pointers via `git reset --soft`, and flattened the branch hierarchy cleanly with `git rebase`.

---

## 📂 Project Structure
```text
Git_and_GitHub_Mohammed_Tauseef_Asif_Shaikh/
├── Git_and_GitHub_POC.docx     # Comprehensive documentation with screen captures
├── app.py                      # Core Python Flask app engine 
├── data.json                   # Resolved Task 2 API static data payload
└── templates/
    └── todo.html               # Enhanced multi-field To-Do UI form
```

---

## 🚀 Execution & Deployment Instructions

### 1. Environment Activation
Ensure your Miniconda instance is running and your isolated context workspace is active:
```bash
conda activate devops_course
```

### 2. Dependency Verification
Verify your workspace has the Flask engine and the MongoDB native driver packages configured:
```bash
pip install flask pymongo
```

### 3. Launching the Local Routing Server
Run the application startup file:
```bash
python app.py
```
Open your browser and navigate to `http://127.0.0` to access the To-Do input workspace.
