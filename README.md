# 🧠 CheckIt

**CheckIt** is a smart, AI-powered English learning platform that helps students master vocabulary and reading through interactive tools, visual organization, and real-time feedback. Built for modern learners and educators, CheckIt replaces boring word lists with engaging sticky notes, progress dashboards, and AI-generated reading practice.

## 🌐 Live Now!

🚀 Visit the live site: [https://checkitboard.org](https://checkitboard.org)  
📢 No login required to explore demo features — test it out today!

## ✨ Core Features

🔍 **AI Reading Practice** – Generate personalized reading passages with comprehension questions. Get instant feedback and explanations powered by OpenAI.  
🧷 **Sticky Note Canvas** – Learn vocabulary visually. Add words as sticky notes, organize into “Need to Learn” and “Want to Learn,” decorate, drag, and pin as you like.  
📊 **Progress Tracking Dashboard** – Automatically visualize your learning progress through charts, tables, and test history. See what you’ve mastered and what still needs work.  
📚 **Smart Vocabulary Bank** – Save words with definition, example, type, and custom tags. Features spaced repetition (coming soon).  
🧪 **Custom Test Generator** – Teachers and staff can create quizzes on vocabulary or reading and assign them to students. Results update in real-time.  
👤 **Role-Based Access** – Students manage their own workspace. Staff accounts can monitor, assign, and track across users or classes.

## ⚙️ Tech Stack

- **Frontend**: React.js + Tailwind CSS  
- **Backend**: Firebase (Firestore, Authentication, Hosting)  
- **AI Integration**: OpenAI API for NLP tasks (reading, Q&A, suggestions)

## 🚀 Quick Start (Local Dev)

1. Clone the project:  
   `git clone https://github.com/yourusername/checkit.git && cd checkit`

2. Install dependencies:  
   `npm install`

3. Create a `.env` file with Firebase + OpenAI keys:  
VITE_FIREBASE_API_KEY=your_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_OPENAI_API_KEY=your_openai_key

markdown
Copy
Edit

4. Start the local dev server:  
`npm run dev` → App runs at `http://localhost:5173`

## 🗂️ Project Structure

/src
/components → UI elements (buttons, cards, modals...)
/pages → Main views (Home, Dashboard, Canvas)
/firebase → Firebase config + services
/hooks → Custom React hooks
/utils → Helper functions
/assets → Images, icons
/styles → Tailwind and global styles

markdown
Copy
Edit

## 👨‍🏫 Use Cases

- Students build their own visual word banks and track their learning over time  
- Teachers create assignments and monitor student progress via test results and dashboards  
- School clubs use sticky note boards to gamify word learning or exam prep  
- Admins manage user roles, word sets, and progress across classes

## 🤝 Contributing

We love contributions from the community! If you’re passionate about edtech, React, or AI-powered learning, feel free to fork, create pull requests, or open issues.

## 👨‍💻 Team

- **Frontend Developer**: [Your Name]  
- **Education Lead**: [Collaborator Name]  
- **Backend & Firebase**: [Collaborator Name]

## 📄 License

Licensed under the **MIT License**. See `LICENSE` for details.

---

> Built with ❤️ for students who learn visually, think independently, and grow confidently.
