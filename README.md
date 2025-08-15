
# 📄 AI Resume Critiquer

The **AI Resume Critiquer** is a Streamlit-based web application that uses OpenAI’s latest language models to provide **personalized, structured feedback** on your resume. Whether you’re targeting a specific job role or just want to improve your general presentation, this tool helps you make your resume more impactful and tailored to recruiters’ expectations.

## ✨ Features

* **PDF & TXT Upload** – Upload your resume in PDF or plain text format.
* **Targeted Feedback** – Optionally specify a job role to receive role-specific suggestions.
* **Automated Analysis** – Get feedback on:

  1. Content clarity and impact
  2. Skills presentation
  3. Experience descriptions
  4. Targeted improvements for your desired role
* **Structured Recommendations** – Feedback is delivered in a clear, actionable format with specific suggestions for improvement.

## 🛠️ How It Works

1. **Upload your resume** (PDF or TXT).
2. **Enter your target job role** (optional).
3. Click **Analyze Resume** to generate AI-powered feedback.
4. Review the structured recommendations and refine your resume accordingly.

## 📦 Installation

```bash
git clone https://github.com/emmamannan/AI-Resume-Critiquer.git
cd AI-Resume-Critiquer
pip install -r requirements.txt
```

## 🔑 Environment Variables

Create a `.env` file in the project root and add:

```
OPENAI_API_KEY=your_openai_api_key_here
```

## 🚀 Run the App

```bash
streamlit run main.py
```

## 🧠 Powered By

* [Streamlit](https://streamlit.io/) – For the web interface
* [PyPDF2](https://pypi.org/project/PyPDF2/) – For PDF parsing
* [OpenAI API](https://platform.openai.com/) – For AI-powered resume analysis

## 🌐 Project Link

[**View on GitHub**](https://github.com/emmamannan/AI-Resume-Critiquer)

---

## 📋 Example Output

<img width="1024" height="1536" alt="ai_resume_critiquer_Screenshot" src="https://github.com/user-attachments/assets/1a559f23-608f-406b-a74e-51fbc65da850" />

---
## 📋 Example Text Output

**Input**:

* Resume: PDF containing work history, skills, and education.
* Target job role: *Data Analyst*

**Output**:

```
### Resume Analysis – Target Role: Data Analyst

**1. Content Clarity and Impact**
- Overall clarity is good, but some role descriptions are too generic.
- Consider using more action verbs (e.g., "streamlined", "optimized", "developed") instead of "helped" or "worked on".
- Quantify achievements where possible (e.g., "Improved report generation speed by 30%").

**2. Skills Presentation**
- Core skills like SQL, Python, and Excel are listed but buried under 'Additional Skills'.
- Move these to the top of the skills section.
- Add relevant data visualization tools (e.g., Tableau, Power BI) if you have experience.

**3. Experience Descriptions**
- Experience is relevant, but bullet points lack measurable outcomes.
- Convert vague statements like "worked with data" to specifics: "cleaned and analyzed 1M+ records using Python pandas library".

**4. Specific Improvements for Data Analyst Role**
- Add a 'Projects' section to showcase portfolio or analytics case studies.
- Emphasize analytical tools, statistical methods, and business impact in work history.
- Consider tailoring the summary section to include your interest in data-driven decision-making.

---
Overall, your resume has strong foundational content, but highlighting measurable results and job-specific skills will make it more competitive.
```

---

