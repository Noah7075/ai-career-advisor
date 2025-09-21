# ai-career-advisor

Personalized AI Career Advisor
A comprehensive, AI-powered web application designed to guide students and professionals from skill assessment to job application readiness. This prototype was built for a GenAI hackathon to showcase a full-circle career development journey powered by generative AI.

✨ Core Features
🤖 AI-Powered Recommendations: Get two tailored career paths with detailed descriptions, required skills, salary insights, and job outlooks based on your unique profile.

📝 Smart Resume Builder: Optionally build an ATS-friendly resume. Use the "Improve with AI" feature to transform your experience and project descriptions into professional, achievement-oriented bullet points.

👤 AI Professional Summary: Generate a polished, first-person professional summary for your resume or LinkedIn profile with a single click, based on your skills and education.

📈 Career Growth Insights: Visualize the projected 15-year job market growth for your top career match with an interactive chart.

📄 AI Cover Letter Generator: Instantly generate personalized cover letters for simulated job listings that match your recommended career path.

💬 Live AI Mentor Chat: Open a chat window to ask follow-up questions about your career path, get project ideas, or seek advice from a conversational AI mentor.

🎙️ Mock Interview Prep: Prepare for interviews with AI-generated behavioral and technical questions tailored to your target role.

🚀 Tech Stack
Frontend: HTML5, Tailwind CSS, Vanilla JavaScript (ES6)

AI Engine: Google Gemini API

Libraries: Chart.js (for growth visualization), Font Awesome (for icons)

⚙️ Getting Started
This is a fully self-contained prototype. All you need is a web browser and a Google Gemini API key.

1. Configuration (CRITICAL STEP)
This project uses the Google Gemini API to power its AI features. Before you can run the application, you MUST add your own API key.

Open the index.html file in a text editor.

Use the "Find and Replace" function of your editor:

Find: AIzaSyB0FBnF8QlDZJSxHnYlbDi8ddgkQR1Ik4I

Replace All with your valid Google Gemini API key.

Save the index.html file.

2. Running the Application
Simply open the modified index.html file in any modern web browser (like Chrome, Firefox, or Edge).

🗺️ How It Works
The user journey is designed to be a seamless, multi-step process:

Profile: The user enters their name, education, and skills. They can generate an AI summary and opt-in to build a resume.

Resume (Optional): The user adds work experience and personal projects, using AI to enhance the descriptions.

Goals: The user describes their career interests, which can also be refined by the AI.

Advice: Upon clicking "Get AI Advice," the application sends the complete profile to the Gemini API and displays the comprehensive results page, unlocking all the post-analysis features like the mentor chat and cover letter generator.
