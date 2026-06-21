# AI Job Finder Assistant

## Overview

AI Job Finder is an intelligent job matching workflow built with n8n. It analyzes a candidate's resume, extracts skills using AI, searches online job listings, and recommends suitable jobs automatically.

---

## Features

✅ Resume Upload

✅ PDF Text Extraction

✅ AI Skill Extraction

✅ Web Job Search

✅ AI Job Matching

✅ Match Reason Generation

✅ Automatic Google Sheets Storage

---

## Workflow

1. User submits a form with:
   - Name
   - Location
   - Job Title
   - Resume

2. The PDF resume is extracted.

3. Groq AI analyzes the resume and extracts skills.

4. Apify searches for job opportunities.

5. Gemini AI compares skills with job descriptions.

6. Recommended jobs are generated.

7. Results are saved to Google Sheets.

---

## Tech Stack

- n8n
- Groq (Llama 3.3 70B)
- Google Gemini
- Apify API
- Google Sheets
- JavaScript

---

## AI Models Used

### Groq
- llama-3.3-70b-versatile

### Google Gemini
- gemini-2.5-flash-lite

---

## Use Cases

- Job seekers
- Career assistants
- Recruitment automation
- Resume analysis
- Career recommendation systems

---

## Future Improvements

- Email job recommendations
- LinkedIn integration
- Resume scoring
- ATS compatibility checking
- Daily job alerts

---

## Author

Hattam Waheed