🛡️ BrandGuard AI

AI-Powered Brand Compliance & Marketing Content Review

BrandGuard AI helps businesses review marketing content against their brand guidelines using AI-powered analysis and rule-based checks.

The goal is to identify potentially risky wording, improve consistency, and help teams create clearer, more brand-aligned content.

🚀 Live Demo

Website: https://thehussainx.github.io/Brandguard-AI/

✨ Features

- AI-Powered Review: Uses Google Gemini to analyze marketing content and provide actionable feedback.
- Rule-Based Checks: Checks content against configured brand rules and restrictions.
- Risk Identification: Highlights potential wording and brand compliance concerns.
- Brand Guideline Alignment: Reviews content against user-provided brand settings.
- Suggested Improvements: Provides recommendations and an optional revised draft.
- Custom Brand Settings: Supports brand name, content type, preferred tone, restricted phrases, required phrases, and terminology rules.
- Secure Backend Integration: Calls the Gemini API through a serverless backend instead of exposing the API key in frontend code.

⚙️ How It Works

1. The user enters marketing content and configures brand guidelines.
2. The frontend performs its configured rule-based checks.
3. The user requests an AI review.
4. The backend sends the content and relevant brand settings to the Google Gemini API.
5. The AI returns an assessment, potential risks, guideline-alignment feedback, and suggested improvements.
6. The results are displayed on the website.

🧰 Tech Stack

- Frontend: HTML, CSS, JavaScript
- AI: Google Gemini API
- Backend: Node.js serverless function
- Deployment: GitHub Pages and Vercel
- Version Control: Git and GitHub

🔐 Environment Configuration

The backend requires the following environment variables in Vercel:

Variable| Purpose
"GEMINI_API_KEY"| Authenticates requests to the Gemini API
"GEMINI_MODEL"| Specifies the Gemini model to use

Keep API keys private. Never commit secrets or ".env" files containing credentials to GitHub.

🛠️ Local Setup

1. Clone or download this repository.
2. Open "index.html" in a browser to inspect the frontend.
3. Configure the backend in a Vercel project with the required environment variables.
4. Deploy the backend and configure the frontend to use the correct API endpoint.

The AI review feature requires the backend to be deployed and configured correctly.

⚠️ Limitations

- AI-generated assessments may be inaccurate or incomplete.
- A flagged phrase does not automatically mean a policy violation has occurred.
- Results depend on the supplied content, configured brand rules, and AI output.
- Users should verify important findings before making business or compliance decisions.

BrandGuard AI is an assistance tool and does not guarantee brand compliance or provide legal advice.

🎯 Project Goal

The project explores how AI and rule-based validation can work together to help identify potential brand consistency issues and improve marketing content review workflows.

👨‍💻 Author

Muhammad Hussain

Built as a practical software project exploring AI integration, backend development, and brand compliance workflows.

---

BrandGuard AI — Review smarter. Communicate consistently.
