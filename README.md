# 💰 Budgeteer — DivHacks 2025 Project

Budgeteer is a web application designed to help users track, visualize, and optimize their personal finances.
Built during **DivHacks 2025**, the project combines AI-assisted summaries with interactive budgeting tools to make financial literacy accessible and engaging.

---

## 🚀 Features

* 📊 **Dynamic Budget Dashboard** — Real-time income and expense tracking
* 💬 **AI-Powered Financial Insights** — Uses the OpenAI API to generate spending summaries and recommendations
* 🧠 **Personalized Insights** — Summarizes transaction history and suggests savings patterns
* 🧩 **User Authentication** — Secure sign-in flow with Auth0
* 🎨 **Modern UI/UX** — Built with React, Tailwind CSS, and Chart.js

---

## 🛠️ Tech Stack

| Category            | Technologies                  |
| ------------------- | ----------------------------- |
| **Frontend**        | React, Tailwind CSS           |
| **Backend**         | Node.js, Express              |
| **AI Integration**  | OpenAI API                    |
| **Auth**            | Auth0                         |
| **Database**        | (Optional) MongoDB / Firebase |
| **Version Control** | Git + GitHub                  |

---

## ⚙️ Local Setup

1. **Clone the repository:**
   git clone [https://github.com/rickeychiu/budgeteer.git](https://github.com/rickeychiu/budgeteer.git)
   cd budgeteer

2. **Install dependencies:**
   npm install
   cd server && npm install

3. **Set up your environment variables:**

   Create a `.env` file in the `/server` directory:

   ```
   OPENAI_API_KEY=your_openai_key_here
   AUTH0_CLIENT_ID=your_auth0_client_id
   AUTH0_SECRET=your_auth0_secret
   ```

   ⚠️ **Do not commit this file.**
   `.env` is already listed in `.gitignore` to prevent secrets from being uploaded.

4. **Start the app:**
   npm run dev
   The development server will start at **[http://localhost:3000](http://localhost:3000)**

---

## 🧹 Note on API Keys & Security

During initial development, API keys were accidentally committed in a local `.env` file.
These have been **redacted and removed from Git history** — GitHub’s push protection automatically blocked the push before any data was exposed.

Steps taken:

* `.env` added to `.gitignore`
* All keys replaced with `REDACTED`
* Old API keys revoked and regenerated
* Repository cleaned and re-pushed safely

For future development:
Keep all environment variables in a local `.env` file only — **never commit secrets** to version control.

---

## 👥 Contributors

**Rickey Chiu** — Frontend, AI Integration, UI Design
**Ashley Hong & Layth Rahman** — Backend & Authentication

---

## 📄 License

This project was created for **DivHacks 2025** and is intended for educational and demonstration purposes.

---

## 💡 Future Improvements

* Add persistent user data storage (MongoDB or Firebase)
* Implement advanced financial forecasting models
* Enhance AI interpretability and feedback explanations
* Deploy production build with CI/CD and SSL

