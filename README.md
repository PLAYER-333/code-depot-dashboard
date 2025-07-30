# 🚀 Code Depot

**Manage Your Code Like Never Before**

Code Depot is a fully client-side, GitHub-powered code management tool designed for students, developers, professionals, and educators. Built with a stunning UI using glassmorphism and vibrant effects, it simplifies pushing, browsing, and organizing code across repositories — all from your browser.

---

## 🔥 Features

- **Secure Key Access**  
  Each user receives a unique access key to store and organize their code.

- **Full GitHub Integration**  
  Upload, browse, and fetch files directly from your GitHub repository using the GitHub REST API.

- **Fully Client-Side Architecture**  
  No backend, no server — everything runs on the frontend using vanilla JavaScript.

- **Elegant & Responsive UI**  
  Built with TailwindCSS, GSAP animations, and a glowing glass aesthetic. Dark/light theme support included.

- **Get Started in Seconds**  
  Paste your GitHub PAT, generate a key, and start managing code instantly.

---

## 📂 Tech Stack

- **Frontend**: HTML5, CSS3 (Tailwind), JavaScript (Vanilla), GSAP  
- **API**: GitHub REST API  
- **Hosting**: GitHub Pages  

---

## ⚙️ How It Works

1. **Enter or Generate Your Key**  
   Your key determines the storage folder inside the GitHub repo.

2. **Paste and Upload Code**  
   Save code by filename — it's pushed to GitHub under `/code/<key>/filename.ext`.

3. **Browse Repositories**  
   View file trees, copy code, and switch repositories seamlessly.

---

## 🔐 Security Note

The GitHub PAT is required to interact with private repositories. It is **stored in-browser only** (via `localStorage`) and never transmitted externally.  
To maximize safety, fork the repository and replace the token manually for deployment.

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).  
You are free to use, modify, and distribute the code with proper attribution.

---

## 🧠 Author

**Shaurya Bhatt**  
Developed with precision, creativity, and zero backend.  
Inspired by a vision to democratize developer workflows.

> _"Fully vibe-coded to empower the future of digital code management."_

---
