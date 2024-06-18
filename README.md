---

# 🚀 Vidshare - The Ultimate Memes & Short Videos App 

MemeBaaz is your one-stop destination for sharing video clips and images 📸. All submissions go through an admin approval process to maintain the quality of content. 

---

## 🌟 Demo

👉 [Play Store (30K+ Downloads)](https://play.google.com/store/apps/details?id=com.vidshare.vidshare)   

---

## ✨ Features

- 👍 Like/Download/Share Options
- 📜 Infinite Scrolling
- 💰 Google Ad Integration
- 💾 Local Save Functionality
- 👮‍♂️ In-built Admin Page
- 📥 User Uploads Enabled
- 🗃️ Media Caching
- 🔄 Media Compression On Upload
- ❤️ Double Tap Like (Instagram-style)
- ⏩ Pagination

---

## 🛠️ Tech Stack

**Client:** Flutter, Getx, Firebase SDK  
**Server:** Firebase, Cloud Firestore, Cloud Storage

---

## 💻 Run Locally

1️⃣ Clone the repo
```bash
gh repo clone raj0408/vidshare
```

2️⃣ Navigate to project directory
```bash
cd vidshare
```

3️⃣ Install dependencies
```bash
flutter pub get
```

## 📦 Firestore Data Model

To set up the Firestore, use the following schema:

```json
{
  "config": {
    "categories": {
      "data": ["category 1", "category 2"]
    },
    "keys": {
      "key": "12345"
    }
  },
  "content": [
    // Add your media docs here
  ]
}
```

---
