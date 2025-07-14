# community-help-platform
a full stack platform for food and medicine donations with AI features
# 🌍 Community Help Platform

A full-stack platform to support communities by enabling food and medicine donations, powered by AI for accessibility and safety.

---

## ✨ Features

### 🍲 Food Donation
- Upload surplus food for sharing
- Locate nearby community fridges
- Receive notifications when food is available

### 💊 Medicine Donation
- Donate unused, unexpired medicine
- Use AI (OCR) to scan labels and auto-fill info
- Find nearby donation drop-off points

### 🤖 AI Integrations
- 🧠 OCR for medicine label scanning using Tesseract.js
- 🗣️ AI Chatbot for user assistance using OpenAI
- 🧪 (Optional) Food freshness prediction from images

### 🗺️ Community Map
- Visualize NGOs, fridges, donation centers near you

---

## 🛠 Tech Stack

| Layer       | Tech                         |
|-------------|------------------------------|
| Frontend    | React.js                     |
| Backend     | Node.js + Express            |
| Database    | MongoDB Atlas                |
| Auth        | Firebase / JWT               |
| AI Features | Tesseract.js, OpenAI API     |
| Hosting     | Vercel (frontend), Render (backend) |

---

## 🚧 Roadmap

- [x] Setup React frontend
- [x] Create Express backend
- [x] MongoDB schema for donations
- [ ] Firebase/JWT authentication
- [ ] Image uploads via Cloudinary
- [ ] AI OCR integration
- [ ] Admin/NGO Dashboard
- [ ] Google Maps API integration
- [ ] Deployment

---

## 🧠 Learnings

- Full stack app development
- RESTful API design
- AI integration using OCR and LLMs
- User authentication & security
- Working with external APIs (Maps, Cloudinary)

---

## 📦 Setup Instructions (Local)

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/community-help-platform

# Go into folders
cd community-help-platform/client  # for frontend
npm install
npm start

cd ../server                     # for backend
npm install
npm start