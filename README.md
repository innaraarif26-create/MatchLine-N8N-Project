🚀 Matchline — AI Job Description Matcher

Matchline is an AI-powered web application that compares a resume with a job description and instantly generates a match score. It highlights overlapping skills between the resume and job requirements, and also identifies missing skills so users can improve their applications before submitting them.

This project is built using a simple frontend (HTML, CSS, JavaScript) connected to an automation backend using n8n and powered by Google Gemini AI. It runs completely on free-tier tools and does not require any database or authentication system.

✨ Features

Matchline provides instant resume analysis by calculating how well a candidate fits a job description. It uses AI to extract and compare skills from both inputs and returns a structured response that includes a match percentage, a summary of compatibility, matched skills, and missing skills. The interface also includes a visual score animation for better user experience.

🧰 Tech Stack

The frontend is built using HTML, CSS, and JavaScript. The backend automation is handled using n8n workflows. The AI processing is done using Google Gemini API. Communication between frontend and backend happens through webhooks. The project can be hosted easily on platforms like Netlify.

⚙️ How It Works

The user enters a job description and their resume bullets into the interface. This data is sent to an n8n webhook, where it is processed using a Gemini AI node. The AI analyzes both inputs and generates a structured response. The response is sent back to the frontend, where it is displayed as a match score along with matched and missing skills.

🚀 Setup Guide

To run this project, first import the provided workflow into n8n. Then create a free API key from Google AI Studio and add it to the Gemini node inside the workflow. After that, copy the webhook URL from n8n and paste it into the frontend JavaScript file in the WEBHOOK_URL variable.

Once everything is connected, run the workflow in listen mode. Open the HTML file in your browser, paste a job description and resume, and click the compare button to see results.

🌍 Deployment

The project can be deployed easily by uploading the HTML file to Netlify or any static hosting service. Once deployed, you will get a public link that can be shared in portfolios, resumes, or freelance profiles.

📊 Example Output

The system returns a JSON-style response internally that includes a match percentage such as 82 percent, a short summary describing compatibility, a list of matched skills like HTML, CSS, and JavaScript, and a list of missing skills such as AWS or Docker.

💡 Use Cases

This tool is useful for job seekers who want to improve their resumes, students applying for internships, freelancers optimizing proposals, and recruiters who want a quick way to evaluate candidate-job fit.

⚠️ Notes

This project does not use any database and does not store user data. All processing happens in real-time through API calls and automation workflows.

🔥 Future Improvements

Future versions of this project can include PDF resume upload support, ATS scoring simulation, multiple job comparison features, downloadable reports, and user authentication for saving history.

<img width="1881" height="901" alt="image" src="https://github.com/user-attachments/assets/693338b8-2b4d-4fb0-ba80-ed53036fc2ac" />
<img width="1886" height="889" alt="image" src="https://github.com/user-attachments/assets/2ed86433-0cc9-421d-b95e-4974a416e612" />
<img width="1852" height="857" alt="image" src="https://github.com/user-attachments/assets/97d77d45-c27b-4b85-a3d9-74a752ac12cf" />
<img width="1878" height="891" alt="image" src="https://github.com/user-attachments/assets/c68d2ac8-49a2-4240-9feb-4ad74aff9ce7" />






