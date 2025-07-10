# 🚀 DevLinkHub

A modern, open-source web app to **save, organize, and share** helpful developer links.  
Perfect for curating articles, tools, or videos you want to revisit — and share with the world.

![Issues](https://img.shields.io/github/issues/Almansori/DevLinkHub)
![Forks](https://img.shields.io/github/forks/Almansori/DevLinkHub)
![Stars](https://img.shields.io/github/stars/Almansori/DevLinkHub)
![License](https://img.shields.io/github/license/Almansori/DevLinkHub)

---

## ✨ Features

- 📚 Save links with title, description, and tags
- 🔍 Filter by tags or keyword
- 🎨 Responsive UI (Dark/Light mode)
- 🔒 JWT Auth (coming soon)
- 🧠 GitHub login (contribution ready)
- 🌐 Public link collections
- 🔧 REST API backend

---

## 🛠️ Tech Stack

### Frontend
- React
- Tailwind CSS
- React Router

### Backend
- Node.js
- Express.js
- MongoDB
- JWT (planned)
- GitHub OAuth (planned)

---

## ⚙️ Setup Instructions

### 1. Clone the repo
```bash
git clone https://github.com/Almansori/DevLinkHub.git
cd DevLinkHub
```

### 2. Install dependencies

#### Frontend
```bash
cd client
npm install
npm run dev
```

#### Backend
```bash
cd server
npm install
npm run dev
```

> You’ll need a `.env` file for the backend:
```
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret
```

---

## 🧩 Contributing

Contributions are what make the open source community amazing!  
We welcome pull requests, ideas, and suggestions.

### Start contributing:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 💡 Good First Issues
- [ ] Add MongoDB setup to backend
- [ ] Add login + register pages (React)
- [ ] Implement GitHub OAuth
- [ ] Add bookmarking from browser (extension or bookmarklet)
- [ ] Write unit tests for link routes

---

## 📜 License

MIT License © Mohammed Almansori

---

## 🙌 Support

Leave a ⭐️ if you like the project!  
Feel free to open issues or reach out via GitHub.

