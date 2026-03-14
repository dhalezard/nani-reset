![npm bundle size](https://img.shields.io/bundlephobia/minzip/nani-reset)
![npm bundle size](https://img.shields.io/bundlephobia/minzip/nani-reset)
![license](https://img.shields.io/npm/l/nani-reset)
[![npm](https://img.shields.io/npm/v/nani-reset)](https://www.npmjs.com/package/nani-reset)


# nani-reset ✨

a minimal and modern css reset for predictable styling

`nani-reset` removes browser inconsistencies and provides clean, predictable css defaults without enforcing design decisions

perfect for modern frontend projects using tools like react, vite or plain html/css

---

## 🚀 installation

install from npm:

```bash
npm install nani-reset
```

then import it in your project:

```css
@import "nani-reset/reset.css";
```

or the minified version:

```css
@import "nani-reset/reset.min.css";
```

you can also import it from javascript / typescript:

```js
import "nani-reset/reset.css"
```

---

## 🧹 what it does

`nani-reset` provides a clean foundation by:

* removing default margins and paddings
* normalizing the box model
* making media elements responsive by default
* resetting form elements to inherit typography
* removing default list styles
* removing default link styling
* improving text wrapping behavior
* creating a safe stacking context for modern apps

---

## 📦 example usage

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

## ⚙️ features

* modern box-sizing model
* responsive media elements
* neutral form controls
* safe defaults for spa frameworks
* smooth scrolling
* respects reduced-motion preferences
* lightweight (~0.8kb minified / ~0.35kb gzip)

---

## 🎯 goals

the philosophy behind `nani-reset` is simple:

* minimal
* predictable
* modern
* non-opinionated

it avoids forcing typography, layout or visual styles so developers remain in full control

---

## 🧠 why another css reset?

many resets either:

* reset too little
* normalize too much
* or enforce styling decisions

`nani-reset` aims to sit in the middle: a **balanced modern reset** for everyday frontend work

---

## 📄 license

mit © d. h. alezard (nani)
