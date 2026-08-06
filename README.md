# 🤖 BrandGuard AI

### AI-Powered Brand-Safe Marketing Content Generation using n8n, OpenAI & Google Sheets

![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-orange)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4.1-green)
![Google Sheets](https://img.shields.io/badge/Google-Sheets-brightgreen)
![Status](https://img.shields.io/badge/Project-Completed-blue)

---

# 📖 Project Overview

BrandGuard AI is an AI-powered workflow automation system developed as a Capstone Project under the *Gen AI for Business* program.

The system automatically generates brand-safe marketing content by combining approved product information with predefined brand guidelines using OpenAI. The generated content is validated, stored in Google Sheets, and sent for human approval before publication.

This project demonstrates the practical use of Generative AI with responsible Human-in-the-Loop (HITL) validation.

---

# 🎯 Capstone Topic

*Topic 05 – Brand-Safe Content and Campaign Studio*

The project focuses on generating marketing content while ensuring compliance with approved product facts, brand guidelines, and human review before publication.

---

# 🚀 Features

- AI-powered content generation
- Brand guideline enforcement
- Product information retrieval
- Google Sheets integration
- OpenAI integration
- n8n workflow automation
- AI Agent implementation
- Content validation using IF Node
- Human approval workflow
- Automated storage of generated content

---

# 💼 Business Problem

Marketing teams spend significant time creating promotional content while ensuring compliance with brand standards.

Manual workflows often lead to:

- Inconsistent messaging
- Longer turnaround time
- Human errors
- Poor tracking
- Repetitive work

BrandGuard AI automates these tasks while maintaining human oversight.

---

# 💡 Solution

The workflow performs the following steps:

1. Read Product Information
2. Read Brand Guidelines
3. Generate Marketing Content using OpenAI
4. Validate Generated Output
5. Store Generated Content
6. Human Review & Approval

---

# 🏗️ Workflow Architecture


Manual Trigger
      │
      ▼
Google Sheets (Products)
      │
      ▼
Google Sheets (Brand Guidelines)
      │
      ▼
AI Agent (OpenAI)
      │
      ▼
IF Validation
      │
      ▼
Generated_Content Sheet
      │
      ▼
Human Approval


---

# 🛠️ Technology Stack

| Technology | Purpose |
|------------|----------|
| n8n Cloud | Workflow Automation |
| OpenAI API | AI Content Generation |
| Google Sheets | Data Storage |
| AI Agent | Prompt Orchestration |
| IF Node | Output Validation |

---

# 📂 Repository Structure


BrandGuard-AI-Capstone
│
├── README.md
├── Report/
│      BrandGuard_AI_Project_Report.pdf
│
├── Project_Overview/
│      Project_Overview.pdf
│
├── Workflow/
│      BrandGuard_AI_Workflow.json
│
├── Screenshots/
│      Workflow.png
│      AI_Agent.png
│      GoogleSheets.png
│      Validation.png
│      Output.png
│
└── Images/
       Architecture.png


---

# ⚙️ Workflow Explanation

### Step 1

Manual Trigger starts the workflow.

### Step 2

Google Sheets retrieves approved product information.

### Step 3

Google Sheets retrieves approved brand guidelines.

### Step 4

The AI Agent combines both datasets.

### Step 5

OpenAI generates professional marketing content.

### Step 6

The IF node validates that the output exists.

### Step 7

Generated content is stored in the Generated_Content sheet.

### Step 8

The content is marked *Pending* until reviewed by a human.

---

# 📸 Screenshots

Include the following screenshots in the repository.

- Complete n8n Workflow
- AI Agent Configuration
- OpenAI Chat Model
- Google Sheets Product Database
- Brand Guidelines Sheet
- IF Node Validation
- Generated Content Sheet
- Successful Workflow Execution

---

# 🧪 Testing

## Test Case 1

Input:

- Product: Smartphone X
- Audience: Students

Result:

- Marketing content generated successfully
- Validation Passed
- Status: Pending

---

## Test Case 2

Input:

- Product: SmartWatch Pro
- Audience: Professionals

Result:

- Marketing content generated successfully
- Validation Passed
- Status: Pending

---

# 📈 Results

The system successfully:

- Automated marketing content generation
- Reduced manual effort
- Improved brand consistency
- Stored generated campaigns automatically
- Supported responsible AI through human approval

---

# 🔮 Future Enhancements

- Multi-language content generation
- Email approval workflow
- Slack / Microsoft Teams integration
- CRM integration
- Brand compliance scoring
- Analytics dashboard
- Social media publishing

---

# 🎥 Demonstration

The workflow demonstrates:

- Reading product information
- Reading brand guidelines
- AI-powered content generation
- Output validation
- Storage in Google Sheets
- Human approval process

---

# 📚 Learning Outcomes

This project helped develop skills in:

- Workflow Automation
- Prompt Engineering
- OpenAI API Integration
- Google Sheets Automation
- AI Agents
- Responsible AI
- Human-in-the-Loop Systems
- Low-Code Development

---

# 👨‍💻 Author

*Omkar Majhi*

Capstone Project

Gen AI for Business

---

# 📄 License

This project has been developed for *educational and academic purposes* as part of a Capstone Project.

---

# 🙏 Acknowledgements

- OpenAI
- n8n
- Google Sheets
- Gen AI for Business Capstone Program
