
 *Mastry AI – AI Career Coach*

 *📌 Overview*

Mastry AI is an AI-powered career coaching platform that helps users master their career journey by providing tools to *generate professional resumes*, *write cover letters*, and *prepare for interviews*. Built using *Next.js* and *Tailwind CSS*, it offers a modern and intuitive user experience.


 *✨ Features*

* ✅ AI-powered *Cover Letter Generator*
* ✅ **Resume Builder** with PDF download support
* ✅ **Interview Preparation** with quizzes and performance tracking
* ✅ **Authentication System** powered by Clerk (Sign-in & Sign-up)
* ✅ Modern UI built with **Tailwind CSS** for responsiveness

 *🛠 Tech Stack*

* *Frontend:* Next.js (App Router), React
* *Styling:* Tailwind CSS
* **Authentication:** Clerk
* **Other Tools:** ESLint, PostCSS

 *📂 Project Structure*

```
Mastry-AI-Project/
├── actions/              # API actions for cover letter, resume, interview
├── app/                  # Next.js App Router structure
│   ├── (auth)/           # Authentication pages
│   ├── (main)/           # Main application pages
│   │   ├── ai-cover-letter/
│   │   ├── dashboard/
│   │   ├── resume/
│   │   └── interview/
│   ├── globals.css       # Global styles
│   └── layout.js         # Root layout
├── components.json       # Component configuration
├── next.config.mjs       # Next.js configuration
├── tailwind.config.mjs   # Tailwind CSS configuration
├── package.json          # Dependencies & scripts
└── README.md             # Project documentation
```

 *📸 Screenshots & Explanations*
 <img width="1920" height="1030" alt="1stMastry" src="https://github.com/user-attachments/assets/565e178f-8c83-4fba-ab8d-d1c06713b9a0" />


### *1. Sign-In Page*

![Sign-In Page](images/1stMastry.png)
The authentication page where users can sign in using **Google** or their **email address**. Powered by **Clerk**, ensuring secure and easy login.


### *2. Landing Page*

!\[Landing Page]\(images/firstOf Mastry.png)
The homepage introduces the platform, showcasing its value proposition: **Master Your Career with AI**. Users can start their journey or subscribe for updates.

### *3. Resume Builder*

![Resume Builder](images/thirdMas.png)
A fully featured **Resume Builder** where users can enter personal details, work experience, education, and projects. They can **save** their progress and **download a PDF** of the resume.


### *4. Interview Preparation*

![Interview Preparation](images/fifMas.png)
Interactive *Interview Preparation Dashboard* showing performance trends, quiz scores, and the ability to start new quizzes for practice.

## *🤝 Contributing*

Contributions are welcome! Please open an issue or submit a pull request.

## *📜 License*

This project is licensed under the *MIT License*

### Make sure to create a `.env` file with following variables -

```
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
```
