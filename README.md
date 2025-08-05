# 🚀 MCP Gmail Automation using LinkedIn & Cursor AI

This project is built using a **custom MCP (Mail Communication Protocol) server** integrated with **Cursor AI**, **Gmail**, and **LinkedIn**. It automates real-world tasks like:
- Publishing LinkedIn posts with specified content and images
- Fetching LinkedIn profile details
- Creating a custom cover letter for job applications
- Sending personalized job application emails using Gmail

> 🎯 Built during the MCP Mega Workshop by NxtWave.

---

## 📌 Key Features

- ✅ Fetch LinkedIn data using Cursor AI tools
- ✅ Generate and publish LinkedIn posts with content + image
- ✅ Auto-generate professional cover letters (e.g., for Infosys)
- ✅ Send complete job applications via Gmail — all in one flow!
- ✅ Uses Cursor’s Composio tools for seamless automation

---

## 💻 Technologies & Tools Used

- **Cursor AI** (Composio MCP Tools)
- **Python** (backbone logic, MCP server)
- **LinkedIn API** (through Cursor integration)
- **Gmail API** (automated email sending)
- **NxtWave MCP Framework**

---

## 🛠️ How It Works

### 1. **Create a LinkedIn Post**
- Cursor AI checks LinkedIn connection
- Post is published using:
  - User content
  - Image (auto-attached via URL)
  - Cursor executes: `COMPOSIO_EXECUTE_TOOL`

### 2. **Apply for a Job (e.g., Infosys)**
- Fetch LinkedIn profile data using: `COMPOSIO_SEARCH_TOOLS`
- Generate a personalized **cover letter** with:
  - Skills
  - Interests
  - Role-based alignment
- Connect Gmail via Cursor MCP tools
- Send email with subject:  
  `LinkedIn Profile Details & Infosys Job Application - Sree Niveditaa Saravanan`

---

## 📬 Output

- ✅ Post published on LinkedIn with custom message (see screenshot)
- ✅ Email sent to employer with:
  - LinkedIn profile data
  - Custom cover letter
  - Subject & content properly formatted

---


