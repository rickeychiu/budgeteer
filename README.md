# 💰 Budgeteer — DivHacks 2025 Project

Budgeteer is a full-stack web application that helps users analyze, visualize, and understand their personal finances.
Built during **DivHacks 2025**, it integrates directly with the **Capital One API** to provide secure, real-time transaction data — enhanced by **OpenAI-powered financial summaries** that turn raw spending habits into meaningful insights.

This project was selected for DivHacks’ **Finance & AI** challenge track and demonstrates how modern APIs and AI can make financial literacy more accessible.

---

## 🚀 Features

* 🏦 **Capital One API Integration** — Securely fetches live transaction and account data
* 💬 **AI-Powered Financial Summaries** — Uses OpenAI’s API to analyze spending patterns and explain them in plain language
* 📊 **Dynamic Budget Dashboard** — Visualizes monthly trends and categories through interactive charts
* 🔐 **Auth0 Authentication** — Ensures user sessions and financial data remain secure
* 🎨 **Modern Interface** — Built with React, Tailwind CSS, and Chart.js for a clean, responsive experience

---

## 🛠️ Tech Stack

| Category                | Technologies                  |
| ----------------------- | ----------------------------- |
| **Frontend**            | React, Tailwind CSS, Chart.js |
| **Backend**             | Node.js, Express              |
| **APIs**                | Capital One API, OpenAI API   |
| **Auth**                | Auth0                         |
| **Database (optional)** | MongoDB / Firebase            |
| **Version Control**     | Git + GitHub                  |

---

## ⚙️ Local Setup

1. **Clone the repository**
   git clone [https://github.com/rickeychiu/budgeteer.git](https://github.com/rickeychiu/budgeteer.git)
   cd budgeteer

2. **Install dependencies**
   npm install
   cd server && npm install

3. **Set up environment variables**
   Create a `.env` file in `/server` and add your keys:

   ```
   CAPITALONE_API_KEY=your_capitalone_key
   OPENAI_API_KEY=your_openai_key
   AUTH0_CLIENT_ID=your_auth0_client_id
   AUTH0_SECRET=your_auth0_secret
   ```

   ⚠️ `.env` is included in `.gitignore` — **never commit secrets.**

4. **Start the app**
   npm run dev
   Open **[http://localhost:3000](http://localhost:3000)**

---

## 🧹 Note on API Keys & Security

Early in development, API keys were briefly included in local commits.
GitHub’s **push protection** blocked the upload, and all secrets have been **redacted, revoked, and replaced**.
`.env` files are now ignored by default to ensure no sensitive data is exposed.

This project fully complies with **Capital One’s API usage policies** and **OpenAI’s data privacy standards**.

---

## 👥 Contributors

* **Rickey Chiu** — Frontend Development, AI Integration, UI Design
* *(DivHacks teammates)* — Backend Integration, Capital One API, Authentication

---

## 💡 Future Improvements

* Integrate transaction categorization and long-term financial forecasting
* Add persistent data storage with MongoDB
* Expand AI prompts for natural-language budgeting advice
* Deploy production build with HTTPS and CI/CD

---

## 📄 License

Developed for **DivHacks 2025 (Columbia University)** — *Educational and Demonstration Purposes Only*

---

Would you like me to make a shorter version (like a 1/3-length version) that still sounds impressive but fits the GitHub landing view better? It’d show off the Capital One + OpenAI integration right at the top.
