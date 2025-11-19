# 🏁 Competitive Countdown — Jan 2027

A **minimal, competitive-style, fully responsive countdown webpage** that syncs with the user’s local time and counts down to **January 1, 2027**.

---

## 🚀 Features

* ⏳ **Live countdown** (Days, Hours, Minutes, Seconds)
* 🕒 **Real-time sync** with user’s local clock
* 📉 **Progress bar** showing % completed between now and Jan 2027
* 🎨 **Minimal competitive UI** with neon accents
* 📱 **Fully responsive** for desktop, tablet, and mobile
* ⚡ **Lightweight** (pure HTML + CSS + JS)
* 🧩 **No dependencies** — zero external libraries
* ♿ Includes **Reduced Motion** support

---

## 📅 Target Date

The countdown ends at:

```
January 1, 2027 — 00:00 (Local Timezone)
```

You can change it here inside the JS:

```js
const target = new Date(2027, 0, 1, 0, 0, 0, 0);
```

---

## 📁 Project Structure

```
project/
│
├── index.html      # Main countdown page
└── README.md       # Documentation
```

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3**
* **Vanilla JavaScript**

---

## 📱 Responsiveness

The layout automatically adapts to:

* Mobile screens
* Tablets
* Desktops

The countdown units shrink and reorganize based on screen width.

---

## 🔧 Customization Guide

You can easily customize:

### 🎨 Colors

Modify the root variables in CSS:

```css
:root {
  --accent: #00e6a8;
}
```

### 🕒 Target date

Change the `new Date()` target.

### 🔤 Logo / Title

Update the logo box or heading text in `<header>`.

### ✨ Animation Speed

Edit the interval delay in:

```js
setInterval(update, 250);
```

---

## 🚀 Hosting

You can host it anywhere because it’s a static site:

* **GitHub Pages**
* **Vercel**
* **Netlify**
* **Firebase Hosting**
* Any static hosting environment

---

## 📄 License

This project is free to use, modify, and integrate in your own projects.
