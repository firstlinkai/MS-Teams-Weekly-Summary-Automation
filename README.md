# n8n Template: Weekly MS Teams Activity Summary  

This n8n template lets you summarize individual team member activity on **Microsoft Teams** for the past week and generates a **weekly team report**.  

For remote teams, chat is a crucial communication tool to ensure work gets done. But with so many conversations happening at once and across multiple threads, ideas, information, and decisions usually live in the moment and then get lost — often forgotten by the weekend.  

With this template, that doesn’t have to be the case. AI will crawl through last week’s activity, summarize all messages and replies, and generate a **casual, snappy report** to bring the team back into focus for the new week. A project manager’s dream!  

---

## 🚀 How It Works  
1. A scheduled trigger runs every **Monday at 6am**, collecting all channel messages from the past week.  
2. Messages are grouped by user.  
3. AI analyzes the raw messages and replies, pulling out interesting highlights and key observations (individual reports).  
4. All individual reports are combined into a **team weekly report** that gives a broader view of group activities.  
5. The final team report is posted back to the channel — making it the **first message of the week** for everyone to review with their coffee.  

---

## 📘 How to Use  
- Best used **per project** where most communication happens in a single channel.  
  - Avoid combining multiple channels. Instead, duplicate the workflow for each channel.  
- If needed, filter for **specific team members** to focus reports.  
- Customize the **tone and format** of the report to fit your organization.  
  - For example, use a more formal style if clients or external stakeholders are in the channel.  

---

## ✅ Requirements  
- **Microsoft Teams** (for chat platform)  
- **OpenAI API Key** (for LLM summarization)  

---

## ⚙️ Customizing the Workflow  
- **Change the output**:  
  - If the Teams channel is already busy, consider sending the final report via **email** instead.  
- **Add context**:  
  - Pull in **project metrics** (e.g., production performance, KPIs) to enrich the report.  
- **Extend with AI Agents**:  
  - Query related **knowledge bases or ticketing systems** to attach references or links for added context.  

---

## 📌 Example Use Case  
- Team members discuss feature updates, bug fixes, and customer requests across the week.  
- On Monday morning, the AI report summarizes:  
  - What each team member contributed.  
  - Common discussion points.  
  - Overall project direction and next steps.  
- The whole team starts the week aligned, without needing to dig through chat history.  

---

## 💡 Pro Tip  
Keep the **timing** consistent. Posting the report first thing Monday morning ensures the team sees it as part of their weekly kickoff.  

---
