<<<<<<< HEAD
# Personal Finance Tracker 💰

A modern, responsive personal finance tracking application built with React, Vite, and Recharts. Track your income, expenses, and visualize your financial data with beautiful charts.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18.x-61DAFB?logo=react)
![Vite](https://img.shields.io/badge/Vite-5.x-646CFF?logo=vite)

## ✨ Features

- 📊 **Interactive Dashboard** - View your financial overview at a glance
- 💵 **Income & Expense Tracking** - Add, edit, and delete transactions easily
- 📈 **Visual Analytics** - Beautiful pie charts and bar graphs using Recharts
- 🎨 **Modern UI** - Clean, responsive design with Tailwind CSS
- 💾 **Local Storage** - All data persists in your browser
- 📱 **Mobile Friendly** - Works seamlessly on all devices
- 🌙 **Dark Mode Support** - Easy on the eyes (optional feature)


## 📸 Screenshots

| Dashboard View | Analytics View |
|----------------|----------------|
| ![Dashboard](./personal-finance/public/screenshots/dashboard.png) | ![Charts](./personal-finance/public/screenshots/piechart.png) |

*🖼️ Replace these placeholders with actual screenshots of your project*

## 🛠️ Tech Stack

- **Frontend Framework:** React 18.x
- **Build Tool:** Vite 5.x
- **Styling:** Tailwind CSS
- **Charts:** Recharts
- **Icons:** Lucide React
- **State Management:** React Hooks (useState, useEffect)
- **Storage:** Browser LocalStorage API

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v16 or higher) - [Download here](https://nodejs.org/)
- **npm** (v8 or higher) or **yarn** (v1.22 or higher)
- **Git** - [Download here](https://git-scm.com/)

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/personal-finance-tracker.git
cd personal-finance-tracker
```

### 2️⃣ Install Dependencies

```bash
npm install
# or
yarn install
```

### 3️⃣ Start Development Server

```bash
npm run dev
# or
yarn dev
```

You'll see output like:
```
VITE v5.x ready in 300ms

➜  Local:   http://localhost:5173/
➜  Network: use --host to expose
```

Open your browser and visit 👉 **http://localhost:5173** 🎉

## 📦 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with hot reload |
| `npm run build` | Create production-ready build |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint to check code quality |

## 🏗️ Build for Production

Create an optimized production build:

```bash
npm run build
```

The build files will be generated in the `dist/` folder.

Preview the production build:

```bash
npm run preview
```

Visit **http://localhost:4173** to see the production build.

## 🐳 Docker Support (Optional)

If you prefer using Docker:

### Build Docker Image

```bash
docker build -t personal-finance-tracker .
```

### Run Docker Container

```bash
docker run -p 3000:3000 personal-finance-tracker
```

Then visit 👉 **http://localhost:3000**

## 📁 Project Structure

```
personal-finance-tracker/
├── public/                 # Static assets
│   └── vite.svg
├── src/
│   ├── components/        # React components
│   │   ├── Dashboard.jsx
│   │   ├── TransactionForm.jsx
│   │   ├── TransactionList.jsx
│   │   └── Charts.jsx
│   ├── App.jsx           # Main App component
│   ├── main.jsx          # Entry point
│   ├── index.css         # Global styles
│   └── utils/            # Helper functions
├── .gitignore
├── Dockerfile
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
└── README.md
```

## 🎯 Usage Guide

### Adding a Transaction

1. Click on **"Add Transaction"** button
2. Select transaction type (Income/Expense)
3. Enter amount and category
4. Add optional description
5. Click **"Save"** to record the transaction

### Viewing Analytics

- Navigate to the **Dashboard** to see your balance summary
- Check the **Charts** section for visual breakdown of expenses
- Filter transactions by date range or category

### Managing Data

- **Edit:** Click the edit icon next to any transaction
- **Delete:** Click the trash icon to remove a transaction
- **Export:** Use the export button to download your data as CSV

## 🌐 Deployment

### Deploy to Vercel

```bash
npm install -g vercel
vercel
```

### Deploy to Netlify

```bash
npm run build
# Then drag and drop the 'dist' folder to Netlify
```

### Deploy to GitHub Pages

```bash
npm run build
npm run deploy
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. **Fork** the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a **Pull Request**

## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature idea? Please open an issue [here](https://github.com/yourusername/personal-finance-tracker/issues).

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 Umar Mulla

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 👨‍💻 Author

**Umar Mulla**

- GitHub: [Umar-MultiverseCode](https://github.com/Umar-MultiverseCode)
- LinkedIn: [Umar Mulla](https://www.linkedin.com/in/umar-mulla/)

## 🙏 Acknowledgements

- [React](https://reactjs.org/) - JavaScript library for building user interfaces
- [Vite](https://vitejs.dev/) - Next generation frontend tooling
- [Recharts](https://recharts.org/) - Composable charting library
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Lucide Icons](https://lucide.dev/) - Beautiful & consistent icons
- Open-source community for inspiration and support

## 📊 Project Status

🟢 **Active Development** - This project is actively maintained and open for contributions.

## 💡 Perfect For

- 🎓 **Students** - Great for learning React and modern web development
- 👨‍💻 **Beginners** - Clean code structure and well-documented
- 💼 **Portfolio Projects** - Showcase your full-stack development skills
- 🏢 **Small Businesses** - Manage personal or small business finances

---

<div align="center">

### ⭐ Star this repository if you find it helpful!

**"Track your spending. Grow your savings. Own your future."** 💸

Made with ❤️ by Umar Mulla

</div>
=======
# 💻 Web-Computing Experiments

A collection of 10 hands-on web computing experiments demonstrating core concepts of web technologies, client-server communication, and browser-based computation.

## 📋 Project Overview

This repository contains practical implementations of various web development concepts, ranging from basic HTML structure to advanced React applications and network simulations. Each experiment is self-contained and focuses on specific web technologies.

---

## 🧪 Experiments

### Experiment 1: Basic HTML Structure 📄

**Location:** `Exp1/exp1.html`

**Technologies:** HTML5

**Description:** A simple, single-page website for "Anjuman-I-Islam's Kalsekar Technical Campus" demonstrating fundamental HTML elements including headings, paragraphs, hyperlinks, tables with department information, and a contact form.

**How to Run:**
```bash
# Open the file directly in a web browser
open Exp1/exp1.html
```

---

### Experiment 2: HTML with External CSS 🎨

**Location:** `Exp2/index.html`, `Exp2/styles.css`

**Technologies:** HTML5, CSS3

**Description:** A stylish webpage for "Umar's Book Haven" bookstore demonstrating the separation of content and presentation. The HTML structure is defined in `index.html` while all styling (layout, colors, fonts) is managed through an external stylesheet.

**How to Run:**
```bash
# Open the file directly in a web browser
open Exp2/index.html
```

---

### Experiment 3: Responsive Design with Bootstrap 📱

**Location:** `Exp3/index.html`

**Technologies:** HTML5, Bootstrap 5

**Description:** An online bookstore webpage utilizing Bootstrap 5 framework for responsive, mobile-first design. Features include a navigation bar, hero section, and a grid of book cards that automatically adjusts to different screen sizes.

**How to Run:**
```bash
# Open the file directly in a web browser
open Exp3/index.html
```

---

### Experiment 4: JavaScript Form Validation ✅

**Location:** `Exp4/index.html`, `Exp4/style.css`

**Technologies:** HTML5, CSS3, JavaScript

**Description:** A registration form for "AIKTC Engineering" implementing client-side validation using JavaScript. Validates minimum name length, email format, password requirements, and ensures 10-digit mobile numbers before form submission.

**How to Run:**
```bash
# Open the file directly in a web browser
open Exp4/index.html
```

---

### Experiment 5: Frontend with React and TypeScript ⚛️

**Location:** `Exp5/src/App.tsx`, `Exp5/package.json`

**Technologies:** React, TypeScript, Vite

**Description:** A modern, single-page registration form built with React and TypeScript. Implements state management using React hooks (`useState`) for handling form inputs and validation logic. The project uses Vite for fast development and building.

**How to Run:**
```bash
# Navigate to the experiment directory
cd Exp5

# Install dependencies
npm install

# Start the development server
npm run dev

# The application will be available at http://localhost:5173
```

---

### Experiment 6: Node.js Command-Line Application 🧮

**Location:** `Exp6/calculator.js`

**Technologies:** Node.js

**Description:** A command-line calculator application built with Node.js. Accepts two numbers and an operation (add, sub, mul, div) as user input and outputs the calculated result to the console.

**How to Run:**
```bash
# Navigate to the experiment directory
cd Exp6

# Run the calculator
node calculator.js

# Follow the prompts to enter numbers and select an operation
```

---

### Experiment 7: Network Simulation 🌐

**Location:** `Exp7/Exp7.pkt`

**Technologies:** Cisco Packet Tracer

**Description:** Network simulation file demonstrating networking concepts using Cisco Packet Tracer. This simulation explores network topology design, device configuration, and packet flow analysis.

**How to Run:**
```bash
# Open the file in Cisco Packet Tracer
# File > Open > Navigate to Exp7/Exp7.pkt
```

---

### Experiment 8: Network Simulation 🌐

**Location:** `Exp8/Exp8.pkt`

**Technologies:** Cisco Packet Tracer

**Description:** Advanced network simulation file created with Cisco Packet Tracer, demonstrating additional networking protocols and configurations.

**How to Run:**
```bash
# Open the file in Cisco Packet Tracer
# File > Open > Navigate to Exp8/Exp8.pkt
```

---

### Experiment 9: Network Simulation 🌐

**Location:** `Exp9/Exp9.pkt`

**Technologies:** Cisco Packet Tracer

**Description:** Network simulation file showcasing complex networking scenarios and troubleshooting techniques using Cisco Packet Tracer.

**How to Run:**
```bash
# Open the file in Cisco Packet Tracer
# File > Open > Navigate to Exp9/Exp9.pkt
```

---

### Experiment 10: Reserved for Future Development 🚧

**Location:** `Exp10/`

**Status:** Empty - available for future experiments

---

## ✅ Prerequisites

- **Web Browser:** Modern browser (Chrome, Firefox, Safari, Edge) for Experiments 1-4 🌐
- **Node.js:** Version 14 or higher for Experiments 5 and 6 📦
- **npm:** Comes with Node.js installation
- **Cisco Packet Tracer:** Required for Experiments 7, 8, and 9 🔧

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd Web-Computing
   ```

2. Navigate to the specific experiment directory you want to run

3. Follow the individual experiment instructions listed above

## 📂 Project Structure

```
Web-Computing/
├── Exp1/          # Basic HTML Structure
├── Exp2/          # HTML with External CSS
├── Exp3/          # Responsive Design with Bootstrap
├── Exp4/          # JavaScript Form Validation
├── Exp5/          # React + TypeScript Application
├── Exp6/          # Node.js CLI Calculator
├── Exp7/          # Network Simulation (Packet Tracer)
├── Exp8/          # Network Simulation (Packet Tracer)
├── Exp9/          # Network Simulation (Packet Tracer)
└── Exp10/         # Reserved for Future Development
```

## 🎯 Learning Objectives

- Understand HTML document structure and semantic markup
- Master CSS styling and responsive design principles
- Implement client-side form validation with JavaScript
- Build modern web applications using React and TypeScript
- Develop Node.js command-line applications
- Explore network topology and configuration using simulation tools

## 📝 License

This project is intended for educational purposes.

>>>>>>> 4835c3978f310e4e9fa1bd84ba34fcf8b8dcd962
