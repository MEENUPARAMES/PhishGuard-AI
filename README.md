# 🛡️ PhishGuard-AI

**PhishGuard-AI** is a smart, responsive web application built to detect phishing URLs using machine learning. Users can input any website link and receive an instant classification: **safe** or **fraudulent**. The frontend is developed using modern frameworks like **Next.js (App Router)**, **TypeScript**, and **Tailwind CSS**, with plans to integrate a trained **Python ML model** (XGBoost) via API.

---

## 🚀 Project Highlights

- ✅ Real-time phishing detection UI
- 💡 Planned integration with an ML backend (Python + XGBoost)
- 🎨 Elegant and accessible UI using Radix UI + Tailwind
- 🧠 Modular design with reusability and clean code

---
## 🧠 Tech Stack

### Frontend
| Tool               | Description                                        |
|--------------------|----------------------------------------------------|
| **Next.js**        | App Router-based React framework                   |
| **TypeScript**     | Type-safe development                              |
| **Tailwind CSS**   | Utility-first responsive styling                   |
| **Radix UI**       | Accessible headless UI components                  |
| **Lucide React**   | Icon library                                       |
| **React Hook Form + Zod** | Form handling and validation               |
| **Embla Carousel, Recharts** | UI enhancements, sliders, and charts     |

### Backend (Planned)
| Tool              | Description                                         |
|-------------------|-----------------------------------------------------|
| **Python**        | Core ML logic and feature extraction                |
| **Flask / FastAPI** | REST API for model prediction                    |
| **XGBoost**       | Phishing classifier model                           |
| **Pickle**        | Model saving/loading for deployment                 |

## 📁 Folder Structure

```
PhishGuard-AI/
├── app/               → App Router pages and layout
├── components/        → Reusable UI components
├── public/            → Static files (icons/images)
├── styles/            → Tailwind and global styles
├── tailwind.config.ts → Tailwind configuration
├── tsconfig.json      → TypeScript settings
├── next.config.mjs    → Next.js configuration
├── package.json       → Project dependencies and scripts



---

## 📦 Getting Started

### Prerequisites:
- Node.js 
- npm

### Setup Instructions:

```bash
# Clone the repository
git clone https://github.com/MEENUPARAMES/PhishGuard-AI.git

# Navigate into the project directory
cd PhishGuard-AI

# Install dependencies
npm install

# Start the development server
npm run dev
```

Then visit: [http://localhost:3000](http://localhost:3000) in your browser.

---

## 👩‍💻 Author

**Meenu Parames P**  
B.Tech in Artificial Intelligence and Data Science  
[GitHub Profile →](https://github.com/MEENUPARAMES)
