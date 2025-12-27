# Study-Helper

Build a complete full-stack educational web application for engineering students
with a modern, premium, 3D-style UI and formal typography.

---

## AUTHENTICATION & USER FLOW

1. When the website opens, show a landing page with:

   - Login
   - Register

2. Registration:

   - Only Email and Password
   - Simple and minimal
   - User registers only once

3. Login:

   - Email + Password
   - After login, user should NOT be asked to register again

4. First-time onboarding (ONLY ONCE after registration):

   - Ask user to select:
     • Semester (1–8)
     • Branch
   - Branches must be exactly:
     • CSE
     • CSE-AIML
     • CSE-Cyber Security
     • CSE-Data Science
     • IT
   - Save selected semester and branch in database

5. On future logins:

   - Skip onboarding
   - Directly open user dashboard

6. Login persistence:
   - Keep user logged in until they explicitly logout
   - Login should persist across page refresh and browser reopen

---

## STUDENT DASHBOARD

1. Dashboard should be personalized based on selected semester and branch
2. Show subject cards relevant to that branch & semester
3. Each subject card should display:
   - Subject Name
   - Progress indicator (percentage or progress bar)
   - Continue Learning button (resume last watched video)

---

## SUBJECT FLOW

When a user clicks on a subject:

- Show two options:
  1. Video Lectures
  2. PYQ Papers

---

## VIDEO LECTURES SYSTEM

1. Video Lectures page should be:

   - Unit-wise
   - Topic-wise inside each unit

2. When user clicks a topic:

   - Fetch YouTube video recommendations automatically using:
     • Topic name
     • Subject name
     • Relevant academic keywords
   - Display embedded YouTube videos
   - Videos should play inside the website (no redirection)

3. Resume Learning:
   - Save last watched video and topic
   - On dashboard, show:
     “Continue where you left off”

---

## PROGRESS TRACKING

1. Track subject-wise progress based on:
   - Topics watched
2. Show progress visually:
   - Progress bars or circular indicators
3. Progress should update automatically as user studies

---

## PYQ PAPERS SYSTEM

1. Subject-wise Previous Year Question Papers
2. Year-wise (Mid Sem / End Sem)
3. PDFs should be viewable inside the website
4. Download option should be available

---

## TECH STACK

Frontend:

- React / Next.js
- Tailwind CSS
- Framer Motion for animations
- 3D-style cards with depth & hover effects
- Formal fonts (Inter / Poppins / DM Sans)

Backend:

- Node.js + Express
- Database (MongoDB / Firebase)
- Secure authentication with persistent sessions
- YouTube Data API for video fetching

---

## DESIGN & UI

- Modern EdTech design
- Clean, formal typography
- 3D and catchy but professional UI
- Fully responsive (mobile + desktop)
- Smooth animations and user-friendly navigation

---

## OUTPUT EXPECTATION

- Fully working full-stack website
- Clean and scalable codebase
- Structured data for subjects, units, topics
- Ready for deployment on Netlify / Vercel
- Optimized for performance and usability

Note:
This platform is for educational, non-commercial student use only.
