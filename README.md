# Stylus Mixins

A collection of clean and practical mixins for [Stylus](https://stylus-lang.com/) to help you write faster, cleaner, and more maintainable CSS.

---

**Author:** Dinh Nguyen  
**Website:** [www.dinhnguyen.info](http://www.dinhnguyen.info)  
**License:** MIT / GPL  
**Repository:** [github.com/dinhnguyen/stylus-mixins](https://github.com/dinhnguyen/stylus-mixins)

---

## 📌 Features

- Lightweight, easy-to-use mixins
- Supports both indented and CSS-like Stylus syntax
- Covers common utilities: spacing, sizing, display, positioning
- Includes modern mixins for:
  - Flexbox
  - CSS Grid
  - Transforms
  - Typography helpers
  - Backgrounds and more

---

## 🚀 Getting Started

### 1. Install Stylus (if not already)

```bash
npm install stylus -g
```

### 2. Clone or download the mixins file

```bash
git clone https://github.com/dinhnguyen/stylus-mixins.git
```

### 3. Import the mixins in your `.styl` file

```stylus
@import 'mixins.styl'
```

> Make sure the path to `mixins.styl` is correct relative to your project structure.

### 4. Use the mixins in your Stylus code

```stylus
h1
  dis inline-block
  wh 251px 200px
  bg url('../text-logo.png') no-repeat
  tex-i -9999px
  fo-s 0.0001em
```

Compiles to:

```css
h1 {
  display: inline-block;
  width: 251px;
  height: 200px;
  background: url("../text-logo.png") no-repeat;
  text-indent: -9999px;
  font-size: 0.0001em;
}
```

---

## 📒 Mixin Naming Reference (Examples)

| Mixin     | Description                     |
|-----------|---------------------------------|
| `dis`     | `display` shorthand             |
| `wh`      | `width` + `height`              |
| `bg`      | `background` shorthand          |
| `tex-i`   | `text-indent`                   |
| `fo-s`    | `font-size`                     |
| `flex-c`  | Centered Flexbox container      |
| `abs`     | Absolute positioning            |
| `trf`     | CSS transform shorthand         |

(See full list in `mixins.styl`)

---

## 📦 Changelog

### v2.0
- Added modern CSS mixins:
  - Flexbox helpers (`flex`, `flex-c`, `flex-wrap`, etc.)
  - Grid utilities
  - Transform and transition shorthands
  - Enhanced spacing and layout mixins

### v1.0
- Initial release

---

## 📃 License

Dual-licensed under the **MIT** and **GPL** licenses.  
Use it freely in both personal and commercial projects.

---

## 🙌 Contributions

Feel free to fork, submit pull requests, or suggest improvements!

> Happy coding!  
> — *Dinh Nguyen*
