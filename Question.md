
Question 21 of 21

You just joined LaunchPad Labs as a junior frontend developer. The team has been building a Speaker Spotlight Card page, and the project is sitting on a developer's local machine — no one else can see it.

Your manager has handed you the project files and given you a clear first task:

"Get this live before the meetup. Push it to GitHub, import it into Vercel, configure the project correctly, and send me the live URL."

This is a common real-world task — taking a finished frontend project and making it publicly accessible. Your final deliverable is the live Vercel URL and a screenshot of your dashboard proving it's deployed.

Starter Code
Create a new folder called speaker-spotlight on your computer and create these 3 files inside it exactly as shown below.

index.html - click to expand
style.css - click to expand
README.md - click to expand
Your Tasks
Task 1 - Personalize the Card
Open index.html and make the following 4 changes:

What to change	Where in the file	Example
Replace Speaker Name	<h1 class="name">	<h1 class="name">Ananya Rao</h1>
Replace Role / Title	<p class="role">	<p class="role">AI Engineer & Speaker</p>
Replace topics	The three <span class="topic"> tags	Machine Learning, Web Dev, Cloud
Replace Speaker in avatar URL	The src attribute	seed=Ananya
Note: style.css does not need to be changed. (You can customize it if you want)

Task 2 - Push to GitHub
Vercel deploys directly from a GitHub repository, so your code must be on GitHub first.

Go to https://github.com and create a new repository called speaker-spotlight
Make it Public
Do not initialize it with a README
Run the following commands:
git init
git add .
git commit -m "Initial speaker spotlight card"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/speaker-spotlight.git
git push -u origin main
Task 3 - Deploy on Vercel
Follow these steps:

Step 1: Go to https://vercel.com and sign in using GitHub

Step 2: Click "Add New..." → "Project"

Step 3: Import your speaker-spotlight repository

Step 4: Configure:

Setting	Value
Project Name	speaker-spotlight
Framework Preset	Other
Root Directory	.
Build Command	(leave blank)
Output Directory	(leave blank)
Step 5: Click Deploy

Step 6: Wait for deployment success message

Step 7: Copy your live URL (example):

https://speaker-spotlight-yourname.vercel.app
Step 8: Open the URL and verify your content

Task 4 - Update README and Document
Open README.md
Replace placeholder with your actual Vercel URL
Run:
git add README.md
git commit -m "Add live Vercel URL"
git push origin main
Confirm your Vercel dashboard shows "Ready"
Student Guidelines
Use GitHub login for Vercel
Repository must be public
No placeholder text allowed
Deployment must show "Ready" (green)
README must contain your live URL
Do not include secrets or tokens
Submission Guidelines
Upload a single zip file:

submission.zip
├── index.html
├── style.css
├── README.md
└── screenshots/
    ├── vercel-dashboard.png
    └── live-app.png
Screenshot 1 - Vercel Dashboard
Browser shows vercel.com
Project name speaker-spotlight visible
Status = Ready (green)
Production URL visible
Screenshot 2 - Live App
Your actual name displayed
Your role/title displayed
Your topics visible
URL visible in browser
Screenshots verified — deployment proof complete.

Upload your answer.


Allowed file formats (.zip)

Maximum file size 50.00 MB