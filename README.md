# n8n-ia

## AI-Powered Automation Workflows for Business

We use **AI, automation, and data** to support sustainable and intelligent business practices for small, medium, and large companies. This repository contains a collection of useful n8n workflows that can be easily adapted and reused.

---

## 🚀 Workflows Overview

### 📬 AI-Powered Sustainability Newsletter (GPT-4o)
This workflow delivers automated daily news digests to raise sustainability awareness and promote your business.

**Ideal for:**
- Business owners wanting to promote services or products through an automated newsletter.

---

## 🧠 AI Automated HR Workflow for CV Analysis
Automates job application handling by extracting key CV information, evaluating candidates against job criteria, and storing results in Google Sheets.

---

## 🔍 AI Web Researcher for Sales

**Who is this for?**
- Sales reps and lead generation managers who need personalized prospecting insights.

**Features:**
- Researches Google using SerpAPI.
- Visits and extracts content from websites using a sub-workflow.

---

## 🤖 Automate LinkedIn Outreach with Notion and OpenAI
Use Notion, n8n, and OpenAI to schedule, format, and post engaging LinkedIn content automatically.

**How it works:**
1. Store text + images in a Notion table.
2. Connect to Notion via integration.
3. Enhance content via OpenAI.
4. Publish to LinkedIn.
5. Mark Notion post as "Done."

**Get a free 1-on-1 consultation:**  
[Book on Calendly](https://calendly.com/basant-choudharynz/letshavecoffe)

---

## 🏡 Automated Real Estate Property Lead Scoring
Integrate BatchData into your process to enrich and score real estate leads using actual property data.

---

### 📈 Generate & Enrich LinkedIn Leads
Automate LinkedIn lead generation and enrichment using:
- Apollo.io
- RapidAPI
- Google Sheets
- Mail.so

**Best for:**
- Sales teams
- Founders
- B2B marketers

---

## 🧑‍💻 IT Support Chatbot
Build a conversational AI-powered support assistant using:
- Google Drive
- Pinecone
- Google Gemini or OpenRouter

**What it does:**
- Processes and indexes documentation.
- Answers employee queries using a trained chatbot.

---

## 📧 Gmail AI Auto Responder
Drafts intelligent email replies directly in Gmail.

**Who it's for:**
- Anyone managing high volumes of email or struggling with response wording.

> *Note: Emails are only drafted — not sent automatically.*

---

## 📨 Reply to Outlook Emails with OpenAI
This template enables AI-generated replies in Microsoft Outlook, personalized to your tone and writing style.

**Requirements:**
- Outlook account with credentials
- OpenAI account
- Sample email replies for training

---

## 💬 Sales Support Chatbot
Automate customer interactions for your webshop using a basic sales support chatbot — ideal for solopreneurs and small businesses.

---

## 🔑 Perform SEO Keyword Research & Insights
Use the Ahrefs API and AI to generate keyword research insights and SEO recommendations.

**Perfect for:**
- SEO specialists
- Content marketers
- Digital agencies

---

## 🗺 Scrape Business Leads from Google Maps
Automatically collect business contact data from Google Maps.

**Who it's for:**
- Sales professionals building targeted lists
- Marketers seeking local data
- Researchers doing market analysis

---

---

## 🔗 WordPress-to-Pipedrive Integration: Automating Contact & Lead Management
**$0+ by Basant Choudhary**

This automation streamlines lead capture and follow-up by integrating **WordPress (via Contact Form 7 with a webhook)** with **Pipedrive**.

When a contact form is submitted, the system:
- Creates or updates a contact in Pipedrive.
- Logs the request as a new lead.
- Adds a follow-up task.
- Attaches a detailed note with all submitted information.

This ensures seamless lead management and timely action.

**🔧 How it Works:**

- **Capture Contact Requests:** Uses the Contact Form 7 (CF7) plugin with a webhook extension to receive contact form submissions.
- **Contact Management:** Automatically creates or updates contacts in Pipedrive.
- **Lead Management:** Saves each request into the Pipedrive lead inbox.
- **Task Creation:** Adds a follow-up task for each lead.
- **Note Attachment:** Attaches a comprehensive note with all submitted details to the lead.

**🛠 Step-by-Step Guide:**

- **Estimated Setup Time:** Quick and simple; depends

---

---

## 🧠 LinkedIn Hiring Workflow using n8n
**$0+ by Basant Choudhary**

**LinkedIn Hiring Signal Scraper — Jobs & Prospecting Using Bright Data**

This workflow discovers recent job posts from LinkedIn using Bright Data’s Dataset API, cleans the results, and logs them into Google Sheets. It can be used for both job hunting and identifying high-intent B2B leads based on hiring activity.

---

#### 🎯 Purpose

- **Job Seekers** – Spot relevant openings filtered by role, city, and country.
- **Sales & Prospecting** – Use job posts as buying signals.  
  > If a company is hiring for a role you support (e.g., marketers, developers, ops), it's the perfect time to reach out and offer your services.

---

#### 🛠 Tools & Nodes Required

**n8n Nodes:**
- Form Trigger  
- HTTP Request  
- Wait  
- If  
- Code  
- Google Sheets  
- Sticky Notes (for embedded guidance)

**External Services:**
- Bright Data (Dataset API)  
- Google Sheets

---

#### 🔐 API Keys & Authentication

- **Bright Data API Key:**  
  Add in the HTTP Request headers:  
  `Authorization: Bearer YOUR_BRIGHTDATA_API_KEY`

- **Google Sheets OAuth2:**  
  Connect your account in n8n to allow read/write access to the spreadsheet.

---

#### ⚙️ General Guidelines

- Use descriptive names for all nodes.
- Include retry logic in polling to avoid infinite loops.
- Flatten nested fields (like `job_poster` and `base_salary`).
- Strip out HTML tags from job descriptions for clean output.

---

#### ⚠️ Things to be Aware Of

- Bright Data snapshots take ~1–3 minutes — use a Wait node and polling logic.
- Form filters affect output significantly:
  - Recommended: filter by **"Last 7 days"** or **"Past 24 hours"** for fresh data.
- Avoid hardcoding values in the form — leave optional filters empty if unsure.

---

#### 📤 Post-Processing & Outreach

Once the data lands in Google Sheets, you can:

- Personalize cold emails based on job titles, locations, and hiring signals.
- Send thoughtful LinkedIn messages (e.g., "Saw you're hiring a CMO...")
- Prioritize outreach to companies actively growing in your niche.


## 📎 License
This project is shared for educational and demonstration purposes. Always ensure compliance with API and platform usage terms when implementing workflows in production.
