# AI-Powered LinkedIn Content Repurposer Automation

## Overview

This project is an AI-powered content repurposing workflow built using Relay.app, Google Forms, Google Sheets, and AI-generated text workflows.

The automation transforms a single project update into multiple reusable content formats automatically, including:

- LinkedIn post
- Cohort/project update
- GitHub README summary

The goal was to reduce repetitive manual writing and create a workflow that helps automate personal branding and project documentation.

<img width="1536" height="1024" alt="AI-Powered LinkedIn Content Repurposer Automation" src="https://github.com/user-attachments/assets/af23dcc4-fd18-4aee-b7ea-05c4b8fe1f09" />

---

## Problem Statement

When building projects, the same information often needs to be rewritten multiple times for different platforms such as LinkedIn, cohort updates, GitHub repositories, and portfolios. This process becomes repetitive and time-consuming. The objective of this workflow was to automate content repurposing so one project submission could automatically generate multiple polished content formats.

---

## Tools Used

- Relay.app
- Google Forms
- Google Sheets
- AI Text Generation
- Gmail

---

## Final Workflow

```text
Google Form Submission
        ↓
Relay.app Trigger
        ↓
AI Generates Content Variations
        ↓
Google Sheets Stores Outputs
```

<img width="704" height="497" alt="image" src="https://github.com/user-attachments/assets/ac55438d-effa-418d-bf34-bef8c208913e" />

---

# Automation Steps

---

## 1. Create Google Form

The form collects project details including:

- Project Title
- Tools Used
- Project Summary
- Key Learning

<img width="447" height="577" alt="image" src="https://github.com/user-attachments/assets/da3ebc5d-5323-40a6-9034-6c195d31913f" />

---

## 2. Connect Form Responses to Relay.app

Relay.app triggers automatically whenever a new form response is submitted.

This becomes the starting point of the automation.

<img width="574" height="67" alt="image" src="https://github.com/user-attachments/assets/1f1ad394-7806-4fe2-a4d3-ad287c93b1f8" />

---

## 3. Generate AI Content

An AI writing step was added inside Relay.app.

The AI receives the project details and generates:

1. LinkedIn post
2. Cohort/project update
3. GitHub README summary

### Prompt Used

```text
Using the project details below, generate:

1. A recruiter-friendly LinkedIn post
2. A concise cohort/project update
3. A professional GitHub README summary

Project Title:
{{Project Title}}

Tools Used:
{{Tools Used}}

Project Summary:
{{Project Summary}}

Key Learning:
{{Key Learning}}

Keep the tone professional, concise, and human.
```

<img width="728" height="634" alt="image" src="https://github.com/user-attachments/assets/30373bb1-6879-4054-bdbd-0fe57d4ea6a1" />

---

## 4. Save AI Outputs to Google Sheets

The generated content is automatically saved into Google Sheets.

Columns include:

- LinkedIn Post
- Cohort Update
- GitHub README Summary
- AI Generated Content

<img width="444" height="778" alt="image" src="https://github.com/user-attachments/assets/42657de2-e0d8-46ac-83bc-24e482efacc2" />



<img width="977" height="778" alt="image" src="https://github.com/user-attachments/assets/dd2df586-ae8b-483f-ad5e-b3379c23c567" />


---

# Challenges Faced

## Gemini API Quota Issues

The original workflow was designed using Google AI Studio Gemini inside Zapier. During testing, the Gemini API free-tier quota became exhausted, which caused repeated 429 quota errors and prevented additional AI responses from being generated.

Example error:

```text
Quota exceeded for metric:
generate_content_free_tier_requests
limit: 0
```

---

# What Worked Successfully

- Relay.app workflow automation
- AI content generation
- Google Forms integration
- Google Sheets storage
- Automated content repurposing

---

# Use Cases

This workflow can be adapted for:

- LinkedIn content generation
- Portfolio documentation
- Project update automation
- Cohort/project submissions
- Resume bullet generation
- Medium article drafting
- Internal knowledge documentation

---

# Why This Project Matters

This project demonstrates how automation and AI can reduce repetitive documentation work and streamline personal branding workflows. Instead of manually rewriting the same project update multiple times, the workflow generates reusable content automatically from one input source.

It also highlights practical no-code automation skills relevant to:

- Data Analysts
- Product Analysts
- Product Operations
- AI Workflow Automation Roles
- Content Automation Workflows

---

# Key Learning

This project helped me better understand:

- AI-assisted workflow design
- automation architecture
- prompt engineering
- no-code productivity systems
- structured content repurposing
- troubleshooting API limitations
- integrating multiple cloud tools together

---

# Final Outcome

A fully working AI-powered automation workflow that:

- Collects project updates through a form
- Generates multiple content formats automatically
- Stores generated outputs in Google Sheets
- Sends automated notifications
- Reduces repetitive manual content creation
