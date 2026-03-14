![npm bundle size](https://img.shields.io/bundlephobia/minzip/nani-reset)
![license](https://img.shields.io/npm/l/nani-reset)
[![npm](https://img.shields.io/npm/v/nani-reset)](https://www.npmjs.com/package/nani-reset)


# nani-reset ✨

A minimal, modern and consistent CSS reset.

`nani-reset` removes browser inconsistencies and provides clean, predictable CSS defaults without enforcing design decisions.

Perfect for modern frontend projects using tools like React, Vite or plain HTML/CSS.

---

## 🚀 Installation

Install from npm:

```bash
npm install nani-reset
```

Then import it in your project:

```css
@import "nani-reset/reset.css";
```

or in JavaScript / TypeScript:

```js
import "nani-reset/reset.css"
```

---

## 🧹 What it does

`nani-reset` provides a clean foundation by:

* Removing default margins and paddings
* Normalizing the box model
* Making media elements responsive by default
* Resetting form elements to inherit typography
* Removing default list styles
* Removing default link styling
* Improving text wrapping behavior
* Creating a safe stacking context for modern apps

---

## 📦 Example usage

```css
@import "nani-reset/reset.css";

body {
  font-family: system-ui, sans-serif;
}

main {
  max-width: 1100px;
  margin: auto;
  padding: 2rem;
}
```

---

## 🎯 Goals

The philosophy behind `nani-reset` is simple:

* minimal
* predictable
* modern
* non-opinionated

It avoids forcing typography, layout or visual styles so developers remain in full control.

---

## ⚙️ Features

* Modern box-sizing model
* Responsive media elements
* Neutral form controls
* Safe defaults for SPA frameworks
* Smooth scrolling
* Lightweight (~1kb)

---

## 🧠 Why another CSS reset?

Many resets either:

* reset too little
* normalize too much
* or enforce styling decisions

`nani-reset` aims to sit in the middle: a **balanced modern reset** for everyday frontend work.

---

## 📄 License

MIT © D. H. Alezard (Nani)
