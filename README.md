# 📬 Human-in-the-Loop AI Email Cleanup Agent

An intelligent, AI-powered email management agent that scans your inbox, classifies incoming clutter, and **always asks for your explicit permission** before taking any action.

## 🛡️ Safety & Human-in-the-Loop (HITL)
To prevent accidental data loss, this agent *never* deletes or archives emails automatically. 
1. The AI scans and proposes an action (e.g., archive newsletter, unsubscribe from spam).
2. It sends an interactive notification asking for approval.
3. You choose **Keep**, **Archive**, or **Delete** before any action occurs.

## 🚀 Built With
- **Orchestration:** n8n workflows
- **Intelligence:** LLM prompt classification
- **Integration:** Gmail / IMAP APIs

## 🗺️ Roadmap & Planned Tasks
- [ ] Set up Gmail API triggers in n8n
- [ ] Build LLM prompt pipeline for email categorization
- [ ] Implement Human-in-the-Loop approval wait nodes
- [ ] Create notification handlers for review confirmations
- [ ] Add safety rules (protect VIP sender domains)
- [ ] Write tests and activity logs# email-cleanup-agent
