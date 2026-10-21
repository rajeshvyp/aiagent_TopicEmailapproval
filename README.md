 LinkedIn Post Approval Workflow using n8n

📌 Project Overview

This project automates LinkedIn post creation using AI Agents and n8n. A Writer Agent generates a post based on a user-provided topic, and a Reviewer Agent improves the draft. The final post is sent to Gmail for human approval. Only approved posts are saved to Google Sheets.

🎯 Objective

To build an AI-powered content workflow that generates, reviews, and stores LinkedIn posts with human approval before saving the final content.

🛠️ Tools & Technologies

- n8n — Workflow automation
- AI Agents — Content generation and review
- OpenAI Chat Model — AI-powered writing and editing
- Gmail — Human approval and rejection
- IF Node — Conditional branching based on approval
- Google Sheets — Storage for approved posts

🔄 Workflow Process

1. Topic Form Trigger: Collects the LinkedIn post topic through a form.
2. Writer Agent: Generates a LinkedIn post based on the submitted topic.
3. Reviewer Agent: Reviews and improves the draft for clarity, engagement, and a strong call to action.
4. Gmail Approval: Sends the reviewed post for human approval or rejection and waits for a response.
5. IF Node: Checks the approval result and routes the workflow accordingly.
6. Google Sheets: Saves the date, topic, final post, and status only when the post is approved.

🧠 Key Concepts Learned

- Building multi-agent workflows in n8n
- Using separate AI Agents for writing and reviewing
- Connecting AI models to automation workflows
- Implementing Human-in-the-Loop (HITL)
- Using IF nodes for conditional logic
- Integrating Gmail and Google Sheets
- Testing approval and rejection paths

 ✅ Expected Results

- Approved: The final LinkedIn post is saved to Google Sheets with the status "Approved".
- Rejected: The post is not saved to Google Sheets.

🚀 How to Use

1. Import the workflow JSON into your n8n instance.
2. Configure your AI model credentials.
3. Connect your Gmail and Google Sheets accounts.
4. Select or configure the destination spreadsheet and worksheet.
5. Test the workflow using a sample topic.
6. Review the generated post and approve or reject it through Gmail.

📚 Project Outcome

Successfully built and tested an AI-powered LinkedIn content approval workflow using n8n. The workflow combines automated content generation with human oversight to ensure that only approved posts are stored.

