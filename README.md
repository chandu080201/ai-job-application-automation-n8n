# 🚀 AI Job Application Automation using n8n

An end-to-end automation system that streamlines the job application process by extracting job details from screenshots and generating personalized application emails using AI.

---

## 📌 Overview

This project automates repetitive job application tasks by combining workflow automation, AI, and messaging tools. It captures job posts, extracts key details, matches them with a candidate’s resume, and sends tailored emails to recruiters.

---

## ⚙️ Features

* 📩 Capture job posts via Telegram (screenshot-based input)
* 🧠 Extract job details using AI (OCR + Vision)
* 📄 Analyze candidate resume from Google Drive
* ✉️ Generate personalized job application emails using GPT-4o
* 📬 Automatically send emails to recruiters
* 🔁 End-to-end workflow automation using n8n

---

## 🧠 How It Works

1. User sends a job post screenshot via Telegram
2. Workflow is triggered in n8n
3. Image is processed using AI to extract:

   * Job role
   * Company name
   * Required skills
   * Hiring email
4. Resume is fetched from Google Drive
5. AI compares job requirements with resume
6. Personalized email is generated
7. Email is sent to the recruiter automatically

---

## 🖼️ Workflow Diagram

> Add your workflow screenshot here

```md
![Workflow](./assets/workflow.png)
```

*(Upload your n8n workflow screenshot inside an `assets` folder in your repo)*

---

## 🛠️ Tech Stack

* **n8n** – Workflow automation
* **OpenAI GPT-4o** – Email generation & text understanding
* **Telegram Bot API** – Input trigger
* **Google Drive API** – Resume retrieval
* **OCR / Vision AI** – Job detail extraction
* **SMTP / Gmail** – Email delivery

---

## 📂 Project Structure

```
.
├── assets/
│   └── workflow.png
├── README.md
```

---

## 🚀 Setup Instructions

1. Clone the repository
2. Import workflow into n8n
3. Configure credentials:

   * Telegram Bot
   * OpenAI API
   * Google Drive
   * Email (SMTP/Gmail)
4. Update your resume file in Google Drive
5. Run the workflow

---

## 🎯 Use Case

* Automates repetitive job application tasks
* Helps candidates send faster, personalized applications
* Reduces manual effort and increases efficiency

---

## ⚠️ Limitations

* Requires manual screenshot input (no auto scraping yet)
* Accuracy depends on image clarity
* Hiring email may not always be available

---

## 🔮 Future Improvements

* Auto job scraping (LinkedIn / APIs)
* Resume tailoring per job
* Application tracking dashboard (Notion/Airtable)
* Email reply tracking
* Multi-job batch processing

---

## 👤 Author

**Neelam Venkata Siva Chandu**
📧 [chanduneelam08@gmail.com](mailto:chanduneelam08@gmail.com)
🔗 LinkedIn: *(add your link)*

---

## ⭐ If you found this useful

Give this repo a ⭐ and connect with me on LinkedIn!

