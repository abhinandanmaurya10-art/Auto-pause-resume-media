# 🎬 Pause Video on Tab Change (Chrome Extension)

A simple Chrome Extension that automatically **pauses videos when you switch tabs** and **resumes playback when you return**.

---

## 🚀 Features

* ⏸️ Automatically pauses video when tab becomes inactive
* ▶️ Resumes video when tab becomes active again
* 🌐 Works on all websites (`<all_urls>`)
* ⚡ Lightweight and fast (no external dependencies)

---

## 🛠️ How It Works

This extension uses the **Page Visibility API** to detect when the user switches tabs.

* When the tab is hidden → video pauses
* When the tab is visible again → video resumes

---

## 📂 Project Structure

```
pause-video-extension/
│
├── manifest.json     # Extension configuration
├── content.js        # Main script for video control
└── README.md         # Project documentation
```
## 🔧 Installation Guide

1. Download or clone this repository:

   ```bash
   git clone https://github.com/https://github.com/abhinandanmaurya10-art/pause-video-extension.git
   ```

2. Open Chrome and go to:

   ```
   chrome://extensions/
   ```

3. Enable **Developer Mode** (top-right corner)

4. Click **Load unpacked**

5. Select the project folder

---

## 🧪 How to Use

1. Open any website with a video (e.g., YouTube,Hotstar,Netflix)
2. Play the video
3. Switch to another tab → video pauses automatically
4. Come back → video resumes

---
## 💡 Future Improvements

* Support multiple videos on a page
* Add toggle ON/OFF button
* Support audio players
* Improve compatibility with custom players

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Abhinandan Verma**

---

⭐ If you like this project, don’t forget to star the repository!
