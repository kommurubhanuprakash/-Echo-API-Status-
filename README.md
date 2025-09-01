📘 Echo API Status – Project Documentation
📌 Overview

Echo API Status is a lightweight web application designed to monitor, test, and display the health/status of APIs. It provides a simple and visually clear dashboard to check whether APIs are online, offline, or experiencing issues.

🚀 Features

API Monitoring – Check the status of one or more APIs in real-time.

Status Dashboard – Visual UI to display API health (online/offline).

Lightweight Build – Uses Vite, TypeScript, and Tailwind for fast rendering.

Customizable – Add/remove APIs easily from the config.

Error Handling – Graceful display of failed API responses.

🛠️ Tech Stack

Frontend: HTML, TypeScript, TailwindCSS, Vite

Config/Styling: ESLint, PostCSS

Package Manager: npm / bun

📂 Project Structure
echo-api-status-main/
│
├── node_modules/           # Dependencies
├── public/                 # Public assets
├── src/                    # Source code (core logic & UI)
│
├── .gitignore              # Git ignored files
├── bun.lockb               # Bun lockfile
├── components.json         # UI components config
├── eslint.config.js        # ESLint configuration
├── index.html              # Main HTML entry point
├── package.json            # Project metadata & scripts
├── package-lock.json       # npm lockfile
├── postcss.config.js       # PostCSS config
├── README.md               # Project documentation
├── tailwind.config.ts      # TailwindCSS configuration
├── tsconfig.app.json       # TypeScript app config
├── tsconfig.json           # TypeScript base config
├── tsconfig.node.json      # Node TypeScript config
└── vite.config.ts          # Vite build config

⚙️ Setup Instructions

Clone Repository

git clone https://github.com/yourusername/echo-api-status.git
cd echo-api-status-main


Install Dependencies

npm install
# or
bun install


Run Development Server

npm run dev


Build for Production

npm run build

📊 Usage

Open the app in your browser after running npm run dev.

API endpoints can be configured inside the src/ folder (e.g., config.ts).

Dashboard shows API status in real-time.

🔮 Future Enhancements

Add authentication support for private APIs.

Include uptime tracking & analytics.

WebSocket integration for live push updates.

Export API reports in CSV/PDF format.