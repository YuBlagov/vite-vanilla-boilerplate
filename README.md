# ✨ Image Feed App — Game of Predictions

A simple and interactive web application that displays a collection of images fetched from an external API.  
Built using **HTML**, **CSS**, and **vanilla JavaScript** — no frameworks or external libraries.

🔮 **Prediction mode**: Each image generates a short fun “forecast,” turning the gallery into an engaging game.

---

## 🌐 Live Demo
🚀 **[gameprediction.netlify.app](https://gameprediction.netlify.app)**

---

## 🚀 Overview
The **Image Feed App** demonstrates how to build a dynamic, data-driven web interface using only client-side JavaScript.  
Users can:

- Browse images  
- Like images ❤️  
- Switch themes 🌗  
- Load more content ➕  
- Explore playful predictions 🔮  

Inspired by **Instagram**, **Unsplash**, and interactive visual experiences.

---

## 🧩 Features
- 🔄 **Dynamic image fetching** from a public API  
- ❤️ **Like button** with interaction states  
- 🔮 **Prediction generator** for each image  
- 🌗 **Light/Dark theme toggle**  
- ➕ **Load more** functionality  
- 📱 **Responsive layout** (CSS Grid / Flexbox)  
- 🎨 **Clean, minimal UI**

---

## 🔗 API
Images are fetched from the open **Image Feed API**:  
👉 **[https://image-feed-api.vercel.app/images](https://image-feed-api.vercel.app/images)**

**Example request:**
```js
fetch("https://image-feed-api.vercel.app/images")
  .then(res => res.json())
  .then(data => console.log(data));
```

---

## 📦 Installation
Clone the repository:

```bash
git clone https://github.com/YuBlagov/vite-vanilla-boilerplate
cd vite-vanilla-boilerplate
```

Install dependencies:

```bash
npm install
```

Run locally:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

---

## ⚡ Notes
- All features are built using **vanilla JavaScript** — no frameworks.  
- The **prediction mode** adds a fun, interactive layer to the image feed.  
- Fully **responsive** and works on mobile and desktop.  

---

## ✨ Contributions
Feel free to fork, clone, or modify the project!  
Pull requests and feedback are welcome.  

---

## 📝 License
MIT License
