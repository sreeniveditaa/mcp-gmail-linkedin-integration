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
  - LinkedIn post creation
    <img width="1920" height="1080" alt="Screenshot 2025-08-04 230321" src="https://github.com/user-attachments/assets/32959dbb-ecf5-4600-85e5-0dca92a39e43" />
    <img width="1902" height="927" alt="Screenshot 2025-08-04 230505" src="https://github.com/user-attachments/assets/214b8bc1-a700-4664-b685-82cfa8a406f1" />

  - mail sent using the linkedin data
    <img width="1915" height="815" alt="Screenshot 2025-08-04 232210" src="https://github.com/user-attachments/assets/ec48bff3-ce44-4f9a-8b53-2180a684d104" />
    <img width="1920" height="1080" alt="Screenshot 2025-08-04 232344" src="https://github.com/user-attachments/assets/c7bc97ff-d286-44c0-80b0-9097a3868dbd" />

---


