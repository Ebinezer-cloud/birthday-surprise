# 🎂 Birthday Surprise Website ❤️

<p align="center">
  <strong>A Beautiful Personalized Birthday Surprise Experience</strong>
</p>

<p align="center">
  A romantic and interactive birthday website featuring personalized wishes, animated hearts, confetti celebrations, photo memories, and a custom music player.
</p>

---

## 💖 About the Project

**Birthday Surprise Website** is a personalized birthday celebration website developed using HTML, CSS, and JavaScript.

It creates a special digital birthday experience with beautiful animations, heartfelt messages, personal photographs, and favourite music.

Users can upload their own photos and music, and the website saves them locally in the browser so they remain available when the website is reopened on the same device and browser profile.

## ✨ Features

### 🎀 1. Personalized Birthday Wishes
- Customized birthday greeting.
- Personalized recipient name.
- Heartfelt birthday message.
- Beautiful pink and purple theme.

### ❤️ 2. Animated Effects
- Floating animated hearts.
- Beautiful birthday decorations.
- Interactive confetti celebration.
- Smooth hover animations.
- Glowing text effects.

### 📸 3. Photo Memories Gallery
- Upload multiple photographs.
- Display uploaded pictures in a gallery.
- Remove unwanted photographs.
- Automatically save photos using IndexedDB.
- Restore saved photos when reopening the website.

### 🎵 4. Special Music Player
- Upload custom audio files.
- Save selected music locally.
- Play and pause music.
- Loop audio playback.
- Remove saved music.
- Automatically attempt playback when opening the surprise.

**Note:** Modern browsers may block automatic audio playback. The visitor can use the Play Music button if necessary.

### 💾 5. Persistent Data Storage
- Uses browser IndexedDB.
- Saves uploaded photographs.
- Saves uploaded music.
- Retains saved content after closing and reopening the website.
- No external database required.

### 📱 6. Responsive Design
- Mobile-friendly layout.
- Desktop browser support.
- Flexible photo gallery.
- Responsive buttons and cards.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling and animations |
| JavaScript | Interactive functionality |
| IndexedDB | Persistent browser storage |
| HTML Canvas API | Confetti animation |
| Web Audio / HTML Audio | Music playback |
| CSS Keyframes | Floating hearts and animations |

## 📂 Project Structure

```text
Birthday-Surprise/
│
├── index.html
│   └── Complete birthday website
│
├── README.txt
│   └── Project documentation
│
└── Open Birthday Website.bat
    └── Windows quick launcher
```

## ⚙️ Installation & Setup

No installation or additional dependencies are required.

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Open the Project Folder

```bash
cd Birthday-Surprise
```

### Step 3: Launch the Website

**Windows users:**
- Double-click `Open Birthday Website.bat`.

**Alternative method:**
- Double-click `index.html`.
- Open it using Google Chrome or Microsoft Edge.

### Step 4: Enjoy the Surprise!

- Click Open Your Surprise.
- Upload your favourite photos.
- Select your favourite birthday music.
- Enjoy the celebration!

## 🎨 Personalization

You can customize the birthday website by editing the JavaScript section inside `index.html`.

Find these variables:

```javascript
const GIRL_NAME = "My Princess";

const MESSAGE = `Happy Birthday, ${GIRL_NAME}! ❤️

Today is your special day, and I wish you all the happiness in the world.

Your smile makes every moment beautiful.
Keep smiling and stay blessed.

Once again, Happy Birthday! 🎂❤️`;
```

Change the recipient's name and message according to your preference.

## 🔐 Privacy & Storage

This project uses IndexedDB to store uploaded photographs and audio files directly in the browser.

- No external server is used.
- Uploaded files are not sent to a project backend.
- Saved data belongs to the same browser profile and device.
- Clearing browser data may permanently remove saved uploads.
- Private browsing may not retain the stored data.

## 💻 Requirements

- Windows, macOS, or Linux.
- Modern web browser.
- Google Chrome, Microsoft Edge, Firefox, or Safari.
- No Python installation required.
- No Node.js installation required.
- No external database required.

## 🚀 Future Enhancements

- Custom birthday countdown.
- More interactive animations.
- Additional gallery layouts.
- Multiple birthday themes.
- More personalization options.
- Custom background effects.

## 👨‍💻 Author

**Ebinezer Jeba Samuel**

- 🌐 GitHub: https://github.com/Ebinezer-cloud
- 💻 LeetCode: https://leetcode.com/u/6UPtksX3aM/
- 🔗 LinkedIn: https://www.linkedin.com/in/ebinezer-n-ab8b61392/

## ⭐ Support

If you like this project, don't forget to give the repository a ⭐ on GitHub!

---

<p align="center">
  Made with ❤️, HTML, CSS & JavaScript
</p>

<p align="center">
  <strong>Making Birthdays More Beautiful, One Surprise at a Time! 🎂</strong>
</p>
