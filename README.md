# AI Resume Screening Agent (Make + OpenAI)

An AI-powered recruitment automation workflow built using Make, OpenAI, Google Workspace, and Slack.

This workflow automatically processes candidate resumes submitted through Google Forms, evaluates them using an AI recruitment agent, scores candidate fit, stores structured evaluations, and alerts recruiters about strong applicants.

---

## Features

* Automated resume intake
* AI-powered candidate evaluation
* Resume parsing and analysis
* Knowledge-based hiring rubric retrieval
* Structured candidate scoring
* Google Sheets integration
* Slack recruiter notifications
* Automated hiring workflow
* Evidence-based AI evaluations

---

## Workflow Overview

```text
Google Form Submission
        ↓
Make Trigger
        ↓
Google Drive Resume Retrieval
        ↓
AI Resume Analysis Agent
        ↓
Candidate Evaluation
        ↓
Google Sheets Storage
        ↓
Slack Alert for Strong Candidates
```

---

## Technologies Used

* Make
* OpenAI
* Google Forms
* Google Drive
* Google Sheets
* Slack
* AI Agents
* Retrieval-Augmented Generation (RAG)

---

## AI Evaluation Capabilities

The AI agent evaluates:

* Technical skills
* Work experience
* Education
* Certifications
* Domain expertise
* Leadership indicators
* Resume-job fit
* Hiring risks
* Missing qualifications

It then generates:

* Fit score
* Candidate summary
* Key strengths
* Key gaps
* Interview questions

---

## Use Cases

* AI recruitment automation
* Resume screening
* ATS augmentation
* Candidate ranking
* Recruiter workflow automation
* HR process automation

---

## Future Improvements

* ATS compatibility scoring
* Email automation
* Multi-role evaluation
* Vector database memory
* Candidate ranking dashboard
* PDF report generation
* Multi-agent recruiter workflows

---

## Setup Instructions

### 1. Import Blueprint into Make

Import the provided `.blueprint.json` file into Make.

### 2. Configure Google Form

Create a Google Form with:

* First Name
* Last Name
* Resume Upload

### 3. Configure AI Connection

Add your OpenAI or AI provider connection inside Make.

### 4. Configure Knowledge Base

Upload hiring rubrics and evaluation criteria to the Knowledge tool.

### 5. Configure Slack Notifications

Connect Slack and set recruiter notification channel.

---

## License

MIT
